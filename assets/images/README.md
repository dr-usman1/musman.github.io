# Profile Picture

To add your profile picture:

1. Add your profile picture to this directory with the name `profile.jpg` or `profile.png`
2. Update the `index.html` file to use your picture:
   - Find the line with `<div class="profile-picture">` 
   - Replace it with: `<img src="assets/images/profile.jpg" alt="Profile Picture" class="profile-picture">`
   - Remove the "MU" text inside the div

The recommended image specifications:
- Format: JPG or PNG
- Dimensions: At least 400x400 pixels (square)
- File size: Under 500KB for optimal loading

## Alternative: Using an Online Image

If you want to use an image hosted elsewhere:
- Replace `assets/images/profile.jpg` with the full URL of your image
- Example: `<img src="https://example.com/my-photo.jpg" alt="Profile Picture" class="profile-picture">`

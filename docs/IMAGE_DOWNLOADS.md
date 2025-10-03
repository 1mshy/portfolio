# Missing Skill Icons - Download Instructions

Below are the URLs for the missing skill icons. Download these images and save them to `/public/skills/` with the specified filenames.

## 1. Python (`python.png`)
**URL**: https://www.pngall.com/wp-content/uploads/2016/05/Python-Logo.png
- Size: 256x256
- Format: PNG with transparent background
- Clean, official Python logo

## 2. Java (`java.png`)
**URL**: https://cdn.freebiesupply.com/logos/large/2x/java-4-logo-png-transparent.png
- Size: 2400x4464 (high quality - resize to ~512x512)
- Format: PNG with transparent background
- Official Java logo

## 3. Rust (`rust.png`)
**URL**: https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/rust-programming-language-icon.png
- Size: 512x512
- Format: PNG with transparent background
- Official Rust logo (gear icon)

## 4. Git (`git.png`)
**URL**: https://pngate.com/wp-content/uploads/2025/06/git-Icon-main-logo-symbol-orange-diamond-shape-software-version-control-1.png
- Size: 1600x1200 (resize to ~512x512)
- Format: PNG with transparent background
- Official Git logo (orange diamond)

**Alternative Git URL** (if above doesn't work):
https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png

## 5. AWS (`aws.png`)
**URL**: https://images.seeklogo.com/logo-png/27/1/aws-amazon-web-services-logo-png_seeklogo-272842.png
- Size: 600x600
- Format: PNG with transparent background
- Official AWS logo

---

## Quick Download Commands

You can download these images using curl or wget. Run these commands from the `/public/skills/` directory:

```bash
# Navigate to the skills directory
cd /Users/lucalapenna/Documents/GitHub/space-portfolio/public/skills/

# Download Python logo
curl -o python.png "https://www.pngall.com/wp-content/uploads/2016/05/Python-Logo.png"

# Download Java logo
curl -o java.png "https://cdn.freebiesupply.com/logos/large/2x/java-4-logo-png-transparent.png"

# Download Rust logo
curl -o rust.png "https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/rust-programming-language-icon.png"

# Download Git logo
curl -o git.png "https://pngate.com/wp-content/uploads/2025/06/git-Icon-main-logo-symbol-orange-diamond-shape-software-version-control-1.png"

# Download AWS logo
curl -o aws.png "https://images.seeklogo.com/logo-png/27/1/aws-amazon-web-services-logo-png_seeklogo-272842.png"
```

---

## Note on Image Sizing

Some images may need to be resized to match the existing skill icons (typically 80x80 or similar). You can use an image editor or an online tool to resize them, or use ImageMagick:

```bash
# Install ImageMagick if not already installed (macOS)
brew install imagemagick

# Resize images to 80x80 (example)
magick python.png -resize 80x80 python.png
magick java.png -resize 80x80 java.png
magick rust.png -resize 80x80 rust.png
magick git.png -resize 80x80 git.png
magick aws.png -resize 80x80 aws.png
```

---

## Verification

After downloading, verify the images are in the correct location:

```bash
ls -la /Users/lucalapenna/Documents/GitHub/space-portfolio/public/skills/
```

You should see: `python.png`, `java.png`, `rust.png`, `git.png`, and `aws.png`

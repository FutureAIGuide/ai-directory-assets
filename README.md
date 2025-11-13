# AI Directory Assets

Public CDN for assets used in the AI directory. This repository serves as a centralized location for logos, screenshots, banners, and category icons.

## 🌐 CDN Access

All assets are publicly accessible via GitHub Pages:
```
https://futureaiguide.github.io/ai-directory-assets/{folder}/{filename}
```

For example:
- Logo: `https://futureaiguide.github.io/ai-directory-assets/logos/openai.png`
- Screenshot: `https://futureaiguide.github.io/ai-directory-assets/screenshots/openai-1.png`
- Banner: `https://futureaiguide.github.io/ai-directory-assets/banners/openai.png`
- Category: `https://futureaiguide.github.io/ai-directory-assets/categories/ai-tools.png`

## 📁 Folder Structure

```
ai-directory-assets/
├── logos/          # Company/product logos
├── screenshots/    # Product screenshots
├── banners/        # Banner images for featured items
└── categories/     # Category icons
```

### `logos/`
Contains company and product logos.

**Naming Convention:** `{slug}.png`
- Use the product/company slug (lowercase, hyphenated)
- Format: PNG (preferred), SVG, or JPG
- Recommended size: 512x512px or similar square ratio
- Examples:
  - `openai.png`
  - `anthropic.png`
  - `midjourney.png`

### `screenshots/`
Contains product screenshots and UI previews.

**Naming Convention:** `{slug}-{number}.png`
- Use the product slug followed by a number for multiple screenshots
- Format: PNG or JPG
- Recommended size: 1920x1080px or 16:9 ratio
- Examples:
  - `openai-1.png` (first screenshot)
  - `openai-2.png` (second screenshot)
  - `github-copilot-1.png`

### `banners/`
Contains banner images for featured or promoted items.

**Naming Convention:** `{slug}.png`
- Use the product/company slug
- Format: PNG or JPG
- Recommended size: 1200x630px (Open Graph standard)
- Examples:
  - `openai.png`
  - `featured-tools.png`

### `categories/`
Contains icons representing different categories of AI tools.

**Naming Convention:** `{category-slug}.png`
- Use the category slug (lowercase, hyphenated)
- Format: PNG or SVG (preferred for icons)
- Recommended size: 256x256px or 512x512px
- Examples:
  - `ai-tools.png`
  - `machine-learning.png`
  - `natural-language-processing.png`
  - `image-generation.png`

## 📝 Usage Guidelines

### Adding New Assets

1. **Optimize images** before uploading:
   - Compress PNG/JPG files to reduce file size
   - Use appropriate dimensions (don't upload oversized images)
   - Consider using WebP format for better compression

2. **Follow naming conventions** strictly:
   - Use lowercase letters only
   - Use hyphens (-) to separate words, not underscores or spaces
   - Keep names descriptive but concise

3. **Organize by folder**:
   - Place assets in the correct folder based on their type
   - Don't create subdirectories within these folders

4. **File formats**:
   - **Logos**: PNG with transparency (preferred) or SVG
   - **Screenshots**: PNG or JPG (JPG for photos, PNG for UI)
   - **Banners**: PNG or JPG
   - **Categories**: PNG with transparency or SVG

### Best Practices

- **Resolution**: Use 2x resolution for retina displays (e.g., 1024x1024 for a 512x512 logo)
- **Transparency**: Use PNG with transparency for logos and icons
- **Consistency**: Maintain consistent aspect ratios within each folder type
- **File Size**: Keep individual files under 500KB when possible
- **Copyright**: Only upload assets you have rights to use

## 🚀 GitHub Pages Deployment

This repository is configured to serve assets via GitHub Pages from the `main` branch.

- **Branch**: main
- **Path**: / (root)
- **URL**: https://futureaiguide.github.io/ai-directory-assets/

Assets are automatically available once merged to the main branch. No build process is required.

## 🔧 Development

### Local Testing

To test locally with a simple HTTP server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if http-server is installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then access files at `http://localhost:8000/logos/example-slug.png`

### Example Integration

In your AI directory application, reference assets like:

```html
<!-- Logo -->
<img src="https://futureaiguide.github.io/ai-directory-assets/logos/openai.png" 
     alt="OpenAI Logo" 
     width="100" 
     height="100">

<!-- Screenshot -->
<img src="https://futureaiguide.github.io/ai-directory-assets/screenshots/openai-1.png" 
     alt="OpenAI Screenshot" 
     loading="lazy">

<!-- Banner -->
<meta property="og:image" 
      content="https://futureaiguide.github.io/ai-directory-assets/banners/openai.png">
```

## 📄 License

Please ensure all uploaded assets comply with their respective licenses and usage rights.

## 🤝 Contributing

1. Fork the repository
2. Add your assets following the naming conventions
3. Submit a pull request with a clear description of the assets added
4. Ensure assets are optimized and properly licensed

---

**Note**: Sample placeholder files are included for demonstration purposes. Replace them with actual assets as needed.

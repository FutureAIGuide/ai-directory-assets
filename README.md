# AI Directory Assets CDN

Public asset CDN for the AI Directory project. This repository hosts logos, screenshots, banners, and category images for AI tools and services.

## 📁 Folder Structure

```
ai-directory-assets/
├── logos/          # Company and product logos
├── screenshots/    # Application screenshots
├── banners/        # Banner images for featured content
└── categories/     # Category icon images
```

## 🎨 Asset Guidelines

### Logos (`/logos/`)
- **Format**: PNG with transparent background preferred
- **Size**: 200x200px (square) recommended
- **Naming**: `{slug}.png` or `{slug}-{variant}.png`
- **Examples**: 
  - `chatgpt.png` - Primary logo
  - `chatgpt-1.png` - Alternative logo variant
  - `midjourney.png` - Another app logo

### Screenshots (`/screenshots/`)
- **Format**: PNG or JPG
- **Size**: 1280x720px or 1920x1080px recommended
- **Naming**: `{slug}-{number}.png`
- **Examples**:
  - `chatgpt-1.png` - First screenshot
  - `chatgpt-2.png` - Second screenshot
  - `chatgpt-3.png` - Third screenshot

### Banners (`/banners/`)
- **Format**: PNG or JPG
- **Size**: 1200x400px (3:1 ratio) recommended
- **Naming**: `{slug}.png`
- **Examples**:
  - `chatgpt.png` - Banner for ChatGPT
  - `midjourney.png` - Banner for Midjourney

### Categories (`/categories/`)
- **Format**: PNG with transparent background preferred
- **Size**: 300x300px (square) recommended
- **Naming**: `{category-slug}.png`
- **Examples**:
  - `ai-tools.png` - AI Tools category icon
  - `machine-learning.png` - ML category icon
  - `natural-language.png` - NLP category icon

## 🔗 CDN Usage

Once deployed via GitHub Pages, assets can be accessed at:

```
https://futureaiapi.com/assets/{folder}/{filename}
```

Or via the GitHub Pages URL:

```
https://[username].github.io/ai-directory-assets/{folder}/{filename}
```

### Example URLs:
- Logo: `https://futureaiapi.com/assets/logos/chatgpt.png`
- Screenshot: `https://futureaiapi.com/assets/screenshots/chatgpt-1.png`
- Banner: `https://futureaiapi.com/assets/banners/chatgpt.png`
- Category: `https://futureaiapi.com/assets/categories/ai-tools.png`

## 📤 Contributing

### Adding New Assets

1. **Follow naming conventions** as outlined above
2. **Optimize images** before uploading:
   - Use tools like TinyPNG, ImageOptim, or similar
   - Keep file sizes reasonable (< 500KB for logos, < 2MB for screenshots)
3. **Use appropriate formats**:
   - PNG for logos and images requiring transparency
   - JPG for photographs and screenshots
4. **Place in correct folder** based on asset type

### Slug Format

Slugs should be:
- Lowercase
- Hyphen-separated words
- Alphanumeric characters only
- Descriptive and unique

Examples: `chatgpt`, `midjourney`, `stable-diffusion`, `dalle-2`

## 🚀 GitHub Pages Deployment

This repository is configured to serve assets via GitHub Pages from the `main` branch. All assets in the repository are publicly accessible via the CDN URLs above.

### CORS Configuration

Assets are served with appropriate CORS headers to allow cross-origin requests from the AI Directory application.

## 📋 Sample Files

This repository includes sample placeholder files to demonstrate the structure:
- `logos/example-app.png` - Sample logo
- `screenshots/example-app-1.png` - Sample screenshot
- `banners/example-app.png` - Sample banner
- `categories/ai-tools.png` - Sample category icon

## 📄 License

All assets in this repository are property of their respective owners. This repository serves as a hosting platform for the AI Directory project.

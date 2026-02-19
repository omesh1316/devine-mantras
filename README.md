# Divine Mantras & Shlokas

A simple, SEO-optimized static website for publishing Hindu mantras and shlokas in Sanskrit, Hindi, and English.

## Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ SEO optimized with meta tags, structured data, and sitemap
- ✅ Clean and modern UI
- ✅ Semantic HTML5
- ✅ Fast loading minimal CSS
- ✅ GitHub Pages compatible

## Project Structure

```
/
├── index.html              # Homepage
├── gayatri.html           # Gayatri Mantra page
├── mahamrityunjaya.html   # Mahamrityunjaya Mantra page
├── hanuman-chalisa.html   # Hanuman Chalisa page
├── style.css              # Main stylesheet
├── sitemap.xml            # XML sitemap for search engines
├── robots.txt             # Robots.txt for crawlers
└── README.md              # This file
```

## Setup for GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `divine-mantras` (or any name you prefer)
3. Make it public (required for free GitHub Pages)
4. Initialize with a README (optional)

### Step 2: Upload Files

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/divine-mantras.git
   cd divine-mantras
   ```

2. Copy all the website files to this directory

3. Commit and push:
   ```bash
   git add .
   git commit -m "Initial commit: Divine Mantras website"
   git push origin main
   ```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section (in the left sidebar)
4. Under **Source**, select **main** branch and **/ (root)** folder
5. Click **Save**
6. Your site will be available at: `https://yourusername.github.io/divine-mantras/`

### Step 4: Update URLs

**IMPORTANT:** Before publishing, update all URLs in the following files:

1. **sitemap.xml** - Replace `yourusername` with your GitHub username
2. **robots.txt** - Replace `yourusername` with your GitHub username
3. **All HTML files** - Replace `yourusername` in:
   - Canonical URLs (`<link rel="canonical">`)
   - Open Graph URLs (`<meta property="og:url">`)
   - Twitter Card URLs (`<meta property="twitter:url">`)
   - Structured Data URLs (JSON-LD)

You can use find-and-replace in your editor:
- Find: `yourusername.github.io/divine-mantras`
- Replace: `yourusername.github.io/divine-mantras` (with your actual username)

## Google Search Console Setup

### Step 1: Verify Ownership

1. Go to [Google Search Console](https://search.google.com/search-console)
2. Click **Add Property**
3. Select **URL prefix** and enter: `https://yourusername.github.io/divine-mantras/`
4. Click **Continue**

### Step 2: Verification Methods

Choose one of these methods:

#### Method A: HTML File Upload (Recommended)
1. Download the HTML verification file from Google Search Console
2. Upload it to your repository root directory
3. Commit and push to GitHub
4. Click **Verify** in Google Search Console

#### Method B: HTML Tag
1. Copy the meta tag provided by Google
2. Add it to the `<head>` section of `index.html`
3. Commit and push
4. Click **Verify** in Google Search Console

#### Method C: Domain Name Provider
1. Add a TXT record to your domain's DNS settings
2. Wait for DNS propagation (can take up to 48 hours)
3. Click **Verify** in Google Search Console

### Step 3: Submit Sitemap

1. After verification, go to **Sitemaps** in the left sidebar
2. Enter: `sitemap.xml`
3. Click **Submit**
4. Google will start crawling your site

### Step 4: Request Indexing (Optional)

1. Go to **URL Inspection** tool
2. Enter your homepage URL: `https://yourusername.github.io/divine-mantras/`
3. Click **Request Indexing**
4. Repeat for other pages:
   - `https://yourusername.github.io/divine-mantras/gayatri.html`
   - `https://yourusername.github.io/divine-mantras/mahamrityunjaya.html`
   - `https://yourusername.github.io/divine-mantras/hanuman-chalisa.html`

### Step 5: Monitor Performance

1. Check **Coverage** report to see indexed pages
2. Monitor **Performance** for search queries and impressions
3. Review **Enhancements** for structured data validation

## SEO Features Included

- ✅ Proper `<title>` tags on all pages
- ✅ Meta descriptions and keywords
- ✅ Open Graph tags for social sharing
- ✅ Twitter Card tags
- ✅ Canonical URLs
- ✅ Semantic HTML5 structure (header, nav, main, article, section, footer)
- ✅ Proper heading hierarchy (H1, H2, H3)
- ✅ Breadcrumb navigation with structured data
- ✅ FAQ structured data (JSON-LD)
- ✅ Article structured data
- ✅ XML sitemap
- ✅ robots.txt
- ✅ Mobile responsive design
- ✅ Fast loading CSS

## Customization

### Update Site Name
Replace "Divine Mantras & Shlokas" throughout all HTML files if needed.

### Add More Mantras
1. Create a new HTML file (e.g., `om-namah-shivaya.html`)
2. Follow the structure of existing mantra pages
3. Add link to navigation in all HTML files
4. Update `sitemap.xml`
5. Add to homepage featured mantras section

### Change Colors
Edit CSS variables in `style.css`:
```css
:root {
    --primary-color: #8B4513;
    --secondary-color: #D2691E;
    --accent-color: #FFD700;
    /* ... */
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is open source and available for personal and commercial use.

## Support

For issues or questions, please open an issue on GitHub.

---

**Note:** Remember to replace `yourusername` with your actual GitHub username in all files before publishing!

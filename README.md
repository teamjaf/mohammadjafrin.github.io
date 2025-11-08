# mohammadjafrin.github.io

This repository contains the source for my personal site hosted on GitHub Pages. The landing page introduces me as a
software engineer, highlights areas of focus, and shares ways to connect.

## 🚀 Features

- **Responsive Design**: Works seamlessly on all devices
- **Dark Mode Support**: Automatically adapts to user's system preferences
- **SEO Optimized**: Includes meta tags, Open Graph, and Twitter Cards
- **Accessibility**: Built with semantic HTML and ARIA labels
- **Fast Loading**: Lightweight static site with no dependencies
- **404 Page**: Custom error page for better user experience

## 📁 Project Structure

```
.
├── index.html          # Main landing page
├── 404.html           # Custom 404 error page
├── robots.txt         # Search engine crawler instructions
├── sitemap.xml        # Site map for search engines
├── .nojekyll          # Disable Jekyll processing
└── README.md          # This file
```

## 🛠️ Local Development

You can open `index.html` directly in a browser to preview the page. No additional tooling or build process is required.

### Option 1: Direct File Opening
Simply double-click `index.html` or open it in your preferred browser.

### Option 2: Local Server (Recommended)
For a more realistic preview, use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 🚢 Deployment

This site is automatically deployed to GitHub Pages when you push to the `main` branch.

### Setup Instructions

1. **Repository Setup**: Ensure your repository is named `mohammadjafrin.github.io` (or `username.github.io` for your username)

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Navigate to **Settings** → **Pages**
   - Under **Source**, select **Deploy from a branch**
   - Choose **main** branch and **/ (root)** folder
   - Click **Save**

3. **Deploy**: Push your changes to the `main` branch:
   ```bash
   git add .
   git commit -m "Update site"
   git push origin main
   ```

4. **Access**: Your site will be live at [https://mohammadjafrin.github.io](https://mohammadjafrin.github.io) within a few minutes.

### Custom Domain (Optional)

To use a custom domain:
1. Add a `CNAME` file in the root with your domain name
2. Configure DNS records as per GitHub Pages documentation
3. Enable "Enforce HTTPS" in repository settings

## 📝 Notes

- The `.nojekyll` file ensures GitHub Pages serves the site as static files without Jekyll processing
- The site uses system fonts with Google Fonts as a fallback for better performance
- All external links include `rel="noopener"` for security
- The site is fully static and requires no build process

## 📄 License

This project is open source and available under the MIT License.

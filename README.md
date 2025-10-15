# whitlock.dev

Professional landing page for Adam Whitlock's consulting services.

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📦 Tech Stack

- **[Astro](https://astro.build)** - Static site generator
- **[Tailwind CSS](https://tailwindcss.com)** - Styling
- **GitHub Actions** - CI/CD
- **GitHub Pages** - Hosting

## 🌐 Deployment

This site automatically deploys to GitHub Pages when changes are pushed to the `master` branch.

### Prerequisites

1. Enable GitHub Pages in repository settings:
   - Go to Settings → Pages
   - Source: GitHub Actions
   
2. Ensure the CNAME file points to your custom domain

3. Configure your DNS:
   - Add A records pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Or add CNAME record: `<username>.github.io`

## 📝 Customization

- **Landing page content**: Edit `src/pages/index.astro`
- **Styling**: Modify `tailwind.config.mjs`
- **Site configuration**: Update `astro.config.mjs`

## 📧 Contact

- Email: adam@whitlock.dev
- LinkedIn: [linkedin.com/in/adamwhitlock](https://linkedin.com/in/adamwhitlock)


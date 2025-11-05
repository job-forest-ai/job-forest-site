# 🌲 JobForest Site

JobForest — A community for learning, job seeking, and AI innovation.

## 🚀 Tech Stack

- **Next.js** - React framework
- **Nextra** - Documentation framework
- **TypeScript** - Type safety
- **Vercel** - Deployment platform

## 📦 Installation

```bash
# Install dependencies (using pnpm)
pnpm install

# Run development server
pnpm run dev

# Build for production
pnpm run build

# Start production server
pnpm start
```

## 🛠️ Development

The development server will start on [http://localhost:3000](http://localhost:3000)

### Project Structure

```
├── pages/
│   ├── index.mdx          # Homepage
│   ├── docs/             # Documentation pages
│   │   ├── getting-started.mdx
│   │   ├── guides.mdx
│   │   └── api.mdx
│   └── _app.tsx          # App wrapper
├── theme.config.tsx      # Nextra theme configuration
├── next.config.js        # Next.js configuration
└── vercel.json          # Vercel deployment config
```

## 🚢 Deploy to Vercel

### Option 1: Using Vercel CLI

```bash
# Install Vercel CLI
pnpm add -g vercel

# Deploy
vercel
```

### Option 2: Using GitHub Integration

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your repository
4. Vercel will automatically detect Next.js and deploy

### Option 3: Using Vercel Dashboard

1. Go to [vercel.com/new](https://vercel.com/new)
2. Import your Git repository
3. Configure build settings (already configured via `vercel.json`)
4. Deploy!

## 📝 Customization

### Theme Configuration

Edit `theme.config.tsx` to customize:
- Logo and branding
- Colors and theme
- Navigation
- Footer
- Social links

### Adding Pages

Add new `.mdx` files in `pages/docs/` to create new documentation pages.

### Styling

Nextra uses a clean, modern design. You can customize colors in `theme.config.tsx` using:
- `primaryHue` - Primary color hue
- `primarySaturation` - Primary color saturation

## 📚 Documentation

- [Nextra Documentation](https://nextra.site)
- [Next.js Documentation](https://nextjs.org/docs)
- [Vercel Documentation](https://vercel.com/docs)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

See [LICENSE](./LICENSE) file for details.

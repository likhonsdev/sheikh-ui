# Sheikh-UI: A Modern React Component Library (Geist Design System Inspired)

Sheikh-UI is a comprehensive, modern React component library designed to provide a robust and aesthetically pleasing alternative to existing UI libraries like shadcn/ui. It is heavily inspired by Vercel's Geist Design System, focusing on clean design, accessibility, and an excellent developer experience. This library adopts a 'copy & paste' model, allowing developers to own their code directly and reduce external dependencies.

## Features

- **Geist Design Aesthetics**: Clean, modern styling inspired by Vercel's design system.
- **Accessibility First**: Built on Radix UI primitives with full keyboard navigation and ARIA attributes.
- **Copy & Paste Model**: No package installation required; full code ownership for maximum flexibility.
- **Comprehensive Components**: A wide range of UI components, including:
  - **Navigation**: Menu (Dropdown, Navigation, Context)
  - **Basic Elements**: Button, Card, Input, Badge, Dialog
  - **Advanced Elements**: Table, Tabs, Accordion, Progress, Switch
  - **Interactive Elements**: Liquid Glass Card, Particle Button, Shimmer Text, Bento Grid, Neon Button, Gradient Button, Toggle Switch, Loading Spinner, Floating Input, Animated Card, Morphing Button
- **Interactive Documentation**: Live code previews with Sandpack integration, similar to shadcn/ui.
- **CLI Integration**: Easy component installation via `bunx shadcn@latest add`.
- **TypeScript Support**: Type-safe development for enhanced code quality.
- **Performance Optimized**: Efficient rendering and optimized assets for fast loading times.
- **SEO Friendly**: Includes `robots.txt`, `sitemap.xml`, and `llm.txt` for better search engine visibility.
- **Mobile Responsive**: Designed with a mobile-first approach for seamless experience across devices.

## Getting Started

### Installation

To get started with Sheikh-UI, you can either clone the repository or use the CLI to add individual components.

#### Cloning the Repository

```bash
git clone https://github.com/your-username/sheikh-ui.git
cd sheikh-ui
pnpm install
pnpm dev
```

#### Adding Individual Components (CLI)

Sheikh-UI supports a CLI-based installation similar to shadcn/ui. You can add components directly to your project using `bunx` (or `npx` if you prefer npm/yarn).

```bash
bunx shadcn@latest add https://ui.likhonsheikh.xyz/r/liquid-glass-card.json
```

Replace `liquid-glass-card.json` with the desired component's JSON file from the Sheikh-UI registry.

### Project Structure

```
sheikh-ui/
├── public/
│   ├── robots.txt
│   ├── sitemap.xml
│   └── llm.txt
├── src/
│   ├── App.jsx
│   ├── components/
│   │   ├── ui/ (shadcn/ui-like components)
│   │   ├── navigation.jsx
│   │   ├── sandpack-preview.jsx
│   │   └── component-showcase.jsx
│   ├── examples/ (Component usage examples)
│   ├── registry/
│   │   ├── components/ (Sheikh-UI custom components)
│   │   └── registry.json
│   └── ... (other source files)
├── tailwind.config.js
├── vite.config.js
├── components.json
├── package.json
└── README.md
```

## Development

Sheikh-UI is built with React, Tailwind CSS, and Vite. It uses Radix UI for unstyled, accessible components.

### Prerequisites

- Node.js (v18 or higher)
- pnpm (recommended)

### Running Locally

1. Install dependencies:
   ```bash
   pnpm install
   ```
2. Start the development server:
   ```bash
   pnpm dev
   ```
   The application will be available at `http://localhost:5173`.

## Contributing

We welcome contributions to Sheikh-UI! Please see our `CONTRIBUTING.md` (to be added) for guidelines on how to contribute.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For questions or support, please reach out to Likhon Sheikh:
- GitHub: [github.com/likhonsdev](https://github.com/likhonsdev)
- Telegram: [t.me/likhonsheikh](https://t.me/likhonsheikh)

---

*Built with love by Manus AI and Likhon Sheikh.*


cd src/frontend
pnpm install
pnpm dev        # starts dev server at http://localhost:4321
src/frontend/
├── astro.config.mjs          # Starlight config, plugins, integrations
├── ec.config.mjs              # Expressive Code config (themes, plugins)
├── tsconfig.json              # TypeScript config with path aliases
├── config/                    # Sidebar topics, locales, redirects, cookies, SEO head
│   └── sidebar/               # Sidebar topic modules (7 files)
├── src/
│   ├── content.config.ts      # Content collections (docs, i18n, packages)
│   ├── route-data-middleware.ts
│   ├── assets/                # Images, icons, logos
│   ├── components/            # Custom Astro components
│   │   └── starlight/         # Starlight component overrides
│   ├── content/docs/          # All documentation pages (MDX/MD)
│   ├── data/                  # JSON data files + pkgs/ API reference
│   ├── expressive-code-plugins/  # Custom EC plugins (disable-copy)
│   ├── pages/                 # Astro page routes
│   ├── styles/                # Global CSS (site.css)
│   └── utils/                 # Helpers, package utils, sample tags

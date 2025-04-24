# Nexvisora

A modern UI component library built for performance and accessibility.

[![npm version](https://img.shields.io/npm/v/nexvisora-ui?color=cb3837&logo=npm)](https://www.npmjs.com/package/nexvisora-ui)
[![Bundle Size](https://img.shields.io/bundlephobia/minzip/nexvisora-ui)](https://bundlephobia.com/package/nexvisora-ui)
[![TypeScript](https://img.shields.io/badge/TypeScript-Ready-blue)](https://www.typescriptlang.org/)
[![MIT License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## Features

- **Modern Design System**: Customizable themes and consistent design patterns
- **Performance Focused**: Optimized bundle size and runtime performance
- **Accessibility First**: WCAG 2.1 AA compliant with full keyboard navigation
- **Type Safety**: Built with TypeScript for better development experience
- **Responsive**: Mobile-first approach with adaptive layouts

## Installation

```bash
npm install nexvisora-ui
```

## Quick Start

```jsx
import { Button, ThemeProvider } from "nexvisora-ui";

function App() {
  return (
    <ThemeProvider>
      <Button variant="primary">Get Started</Button>
    </ThemeProvider>
  );
}
```

## Components

Our component library includes:

- **Layout**: Container, Grid, Stack, Divider
- **Forms**: Button, Input, Select, Checkbox
- **Display**: Card, Table, List, Avatar
- **Feedback**: Alert, Modal, Toast, Progress
- **Navigation**: Tabs, Menu, Breadcrumb, Pagination

## Theming

Customize your theme using our theme configuration:

```js
const theme = {
  colors: {
    primary: "#3b82f6",
    secondary: "#10b981",
    // Add more colors
  },
  spacing: {
    sm: "0.5rem",
    md: "1rem",
    lg: "1.5rem",
  },
};
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Community

- [Discord](https://discord.gg/nexvisora)
- [Twitter](https://twitter.com/nexvisora)
- [GitHub Discussions](https://github.com/nexvisora/nexvisora/discussions)

## License

MIT © Nexvisora

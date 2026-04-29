# demo-frontend

Demo client — frontend (UI, pages, checkout flow)

## Overview

`demo-frontend` is the client-side application for the demo platform. It covers the full user-facing experience including browsing, product pages, and the end-to-end checkout flow.

## Getting Started

### Prerequisites

- Node.js ≥ 18
- npm ≥ 9 (or your preferred package manager)

### Installation

```bash
npm install
```

### Development server

```bash
npm run dev
```

The app will be available at `http://localhost:3000` by default.

### Build

```bash
npm run build
```

### Tests

```bash
npm test
```

## Project structure

```
src/
  components/   # Reusable UI components
  pages/        # Route-level page components
  checkout/     # Checkout flow (cart, payment, confirmation)
  styles/       # Global styles and theme tokens
  utils/        # Shared helpers and API clients
```

## Contributing

1. Fork the repository and create a feature branch.
2. Make your changes with appropriate tests.
3. Open a pull request — use the issue templates in `.github/ISSUE_TEMPLATE/` to report bugs or request features before starting larger pieces of work.

## License

MIT

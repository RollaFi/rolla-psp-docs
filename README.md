# Rolla PSP API Documentation

This repository contains the API documentation for [Rolla PSP](https://rolla.io), built with [Mintlify](https://mintlify.com).

## Documentation

Visit the live documentation at [docs.rolla.io](https://docs.rolla.io)

### What's Included

- **Getting Started** - Introduction and authentication guides
- **API Reference** - Complete API endpoint documentation
  - Initiate Payment
  - Verify Transaction
  - Get Transaction Details
- **Webhooks** - Event notifications setup
- **API Keys** - Key management and best practices

## Development

### Prerequisites

- Node.js 18+
- npm or yarn

### Local Development

Install the Mintlify CLI:

```bash
npm i -g mintlify
```

Run the documentation locally:

```bash
mintlify dev
```

The documentation will be available at `http://localhost:3000`.

### Project Structure

```
rolla-psp-docs/
├── mint.json              # Mintlify configuration
├── introduction.mdx       # Getting started guide
├── authentication.mdx     # Authentication documentation
├── api-reference/
│   ├── introduction.mdx   # API overview
│   ├── initiate-payment.mdx
│   ├── verify-transaction.mdx
│   ├── get-transaction.mdx
│   ├── webhooks.mdx
│   └── api-keys.mdx
└── images/
    ├── logo-light.svg
    ├── logo-dark.svg
    └── favicon.svg
```

## Deployment

This documentation is automatically deployed via GitHub integration with Mintlify. Push changes to the main branch to trigger a deployment.

### Manual Deployment

If needed, you can trigger a manual deployment:

```bash
mintlify deploy
```

## Contributing

1. Make your changes to the `.mdx` files
2. Test locally with `mintlify dev`
3. Submit a pull request

## Resources

- [Rolla Dashboard](https://merchant.rollapay.com)
- [Mintlify Documentation](https://mintlify.com/docs)
- [Support](mailto:support@rolla.io)

## License

Copyright 2024 Rolla. All rights reserved.

# ZetaChain Frontend Omnichain NFT template

This repository provides a frontend app template for developers looking to build
applications on ZetaChain. It's designed to demonstrate various ZetaChain
functionalities and serve as a starting point for custom DApp development.

![Screenshot](./public/screenshot.png)

The dApp is built with [Next.js](https://nextjs.org/),
[Tailwind](https://tailwindcss.com/), [shadcn/ui](https://ui.shadcn.com/), and
the [ZetaChain Toolkit](https://github.com/zeta-chain/toolkit/).

## Features

- Portfolio view with token balances
- Omnichain swaps
- Token deposit and withdrawal
- Cross-chain transaction tracking
- Cross-chain messaging example
- Bitcoin support

## Prerequisites

- Node.js v18
- Yarn

The ZetaChain Toolkit is initialized with a custom RPC endpoint for ZetaChain to
ensure that requests are not rate-limited. By default we're using an RPC endpoint
provided by [AllThatNode](https://www.allthatnode.com/zetachain.dsrv).

Before starting the development server:

- Sign up for a free tier account at [AllThatNode](https://www.allthatnode.com/)
  and copy the API key from the dashboard into a `.env.local` file as a
  `NEXT_PUBLIC_ATN_API_KEY` variable.
- Or replace the RPC in `ZetaChainContext.tsx` with the endpoint of your choice.

## Getting Started

Start a development server:

```
yarn dev
```


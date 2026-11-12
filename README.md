# MallDash Vendor

The shop owners' app of **MallDash**: each shop sees its own orders and updates their status, manages its products, prices, discounts and stock, its staff accounts and its shop profile, with a sales dashboard. English, Arabic and Kurdish, light and dark.

> **Live demo:** https://malldash-vendor-demo.vercel.app (sign in with `vendor@malldash.demo` / `demo1234`)
> The demo answers from made-up data inside your browser (`src/demo/server.ts`), so nothing real is shown and your changes stay on your device. The admin dashboard: [malldash-admin](https://github.com/Mhamad-Raad/malldash-admin).

**Stack:** React, TypeScript, Vite, Redux Toolkit, Tailwind CSS with Radix UI (shadcn/ui), i18next, Recharts, axios, SignalR for live notifications.

```bash
npm install
npm run dev                         # needs the MallDash API in VITE_API_URL
npx vite --mode demo                # or: run on the built-in demo data
```

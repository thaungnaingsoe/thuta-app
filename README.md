# Property Portal Web App

React + TypeScript + Vite web client. Initialized with shadcn preset `b7ClNFsdu` (Luma style, Mist base, Emerald theme, Inter, Phosphor icons). Its generated configuration and theme tokens are in `components.json` and `src/index.css`; the MVP composes its page UI with custom CSS alongside the shadcn theme setup.

## Run locally

```sh
npm install
cp .env.example .env.local # optional
npm run dev
```

Set `VITE_API_URL` to the API origin if it is not `http://localhost:4000`. With the API unavailable, the browse experience uses its built-in demo listings.

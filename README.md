# Voting System Frontend

Blockchain-based voting system for secure elections built with Next.js, Tailwind CSS, and Web3.

## Getting Started

1. Copy the environment variables:
```bash
cp .env.example .env.local
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser.

## Environment Variables

| Variable | Description |
|---|---|
| `NEXT_PUBLIC_API_URL` | Live or local backend endpoint (default: `http://localhost:3001`) |
| `NEXT_PUBLIC_FACTORY_ADDRESS` | Deployed UUPS ElectionFactory Proxy address on Sepolia |
| `NEXT_PUBLIC_BACKEND_VERIFIER` | Public address of the backend verifier |
| `NEXT_PUBLIC_ADMIN_ADDRESS` | Public address of the admin |

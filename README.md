
Fitness App (with Indian Vegetarian option)
-------------------------------------------

Quick start (local):
1. Install pnpm if you don't have it:
   npm install -g pnpm

2. From the repo root:
   pnpm install
   pnpm dev:web   # runs Next.js web at http://localhost:3000

3. To run mobile dev (Expo) (placeholder app included):
   cd apps/mobile
   pnpm install
   pnpm start

What's inside:
- apps/web: Next.js web app (Planner UI with Indian Vegetarian recipes)
- apps/mobile: Expo mobile placeholder
- packages/shared: placeholder for shared logic
- .github/workflows: CI stubs for web build and EAS mobile build
- vercel.json: Vercel monorepo config

Next steps (deploy & stores):
- Push repo to GitHub
- Connect GitHub -> Vercel and set project root to /apps/web (Vercel will auto-deploy)
- Buy a domain on any registrar (Namecheap, Google Domains, GoDaddy) and add it in Vercel -> Domains. Follow Vercel DNS instructions.
- Configure Expo & EAS to build Android (AAB) and iOS (archive). Create Google Play dev account ($25 one-time) and Apple Developer account ($99/yr).
- Use EAS builds to generate signed binaries and upload to stores (Test track / TestFlight) for testing, then publish.

This README contains a short summary. Detailed step-by-step deployment instructions are provided in the chat message after the ZIP download link.

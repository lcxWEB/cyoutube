bunx create-next-app@15.1.6

## UI
bunx --bun shadcn@2.1.8 init  
bunx --bun shadcn@2.1.8 add --all

## Clerk Auth
bun add @clerk/nextjs@6.10.3     

## Database PosgreSQL Drizzle
bun add drizzle-orm@0.39.0 @neondatabase/serverless@0.10.4 dotenv@16.4.7
bun add -D drizzle-kit@0.30.3 tsx@4.19.2
bunx drizzle-kit push 
bunx drizzle-kit studio

## WebHook
install ngrok
https://dashboard.ngrok.com/domains
ngrok config add-authtoken xxx
ngrok http --url=giving-oddly-flea.ngrok-free.app 3000

bun add concurrently@9.1.2

bun add svix@1.45.1




## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

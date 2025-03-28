This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

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

## Packages needed

npx create-next-app@latest .

## How to properly connect the env variables

1. Follow: https://docs.convex.dev/quickstart/nextjs
2. Check THE README.md from CONVEX folder as well for more in depth knowledge about how convex works
3. Create your schemas. This template already comes with 3 predefined ones that can be updated based on needs.
4. CRUD operations for users: users.ts
5. http.ts file where you define your webhook call
6. Follow: https://docs.convex.dev/auth/clerk
7. Clerk -> JWT Token -> new template -> do not rename, leave it convex -> copy issuer URL -> apply changes
8. Create auth.config.ts
9. npm install @clerk/nextjs if you use nextjs otherwise continue with the react version
10. clerk publishable key
11. configure convex provider with clerk
12. webhook -> convex domain -> append .convex.site/clerk
13. super simple guide for doing the whole process https://www.youtube.com/watch?v=zfAb95tJvZQ&t=3516s

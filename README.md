This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

# Email Classifier App (In Progress)

This is a Next.js + Tailwind CSS project for building an Email Classifier App.  
The app will allow users to log in with Google OAuth, fetch Gmail emails, and classify them using OpenAI GPT.

---

## Current Status

- Project initialized with Next.js 16 / Turbopack
- Tailwind CSS installed and configured (globals.css ready)
- `.env.local` created for storing environment variables (Client ID, Secret, OpenAI Key)
- Basic `page.tsx` with OpenAI Key input and Google Login button (frontend skeleton)

**Known Issue:**  
Currently, the project shows the following build error when running the dev server:

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




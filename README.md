# 🛒 বাজার দর (BazarDor)

বাজার দর is a Bangladeshi grocery price tracker. It shows today's market-wise prices for rice, lentils, oil, vegetables, fish, meat, eggs and spices, along with daily price changes.

🔗 **Live:** https://YOUR-LIVE-LINK.vercel.app

## ✨ Key Features

1. **Live price ticker**: an infinite marquee showing every product's price and ▲/▼ change.
2. **Top 6 risers and fallers**: see which prices went up or down today.
3. **Category pages**: filter by category with sorting (default, low to high, high to low) and skeleton loaders.
4. **Protected product details**: min, max and average price plus a market-wise price table (login required).
5. **Authentication**: email/password, Google and GitHub login with Better Auth, toast notifications, and profile name update.
6. **Fully responsive**: works on mobile, tablet and desktop, with a custom 404 page.

## 🧰 Technologies Used

- Next.js (App Router) and TypeScript
- Tailwind CSS and DaisyUI
- Better Auth with MongoDB
- react-hot-toast and lucide-react

## 🚀 Run Locally

```bash
npm install
npm run dev
```

Create a `.env` file:

```
BETTER_AUTH_SECRET=
BETTER_AUTH_URL=http://localhost:3000
NEXT_PUBLIC_APP_URL=http://localhost:3000
MONGODB_URI=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=
```

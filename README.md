This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).
# 🎬 Reels Pro – Share Your Moments, One Reel at a Time

**Reels Pro** is a modern social video-sharing app where users can upload short videos (reels), like, explore, and interact with others. Built using cutting-edge full-stack technologies like Next.js, MongoDB, and ImageKit for a fast and smooth user experience.

---

## 🚀 Tech Stack

- ⚡️ **Next.js 14 (App Router)**
- 🔐 **NextAuth.js** – Authentication
- 🔒 **bcrypt.js** – Password hashing
- 🧠 **Mongoose** – MongoDB ODM
- 🖼 **ImageKit** – Media uploads + CDN delivery
- 🎨 **Tailwind CSS** – UI Styling
- 💻 **TypeScript** – Type safety

---

## 🔧 Features

- 🔐 **User Authentication**
  - Sign up / Login with Google or Email
  - Secure password storage using bcrypt

- 📹 **Upload Reels**
  - Upload short videos with captions
  - Store media on ImageKit CDN

- ❤️ **Engagement**
  - Like and view other reels
  - Real-time like counters

- 👤 **Profile Page**
  - View your uploaded reels
  - Update your profile info and avatar

- 🔍 **Explore Page**
  - Browse all reels
  - Discover trending content

---

## 📁 Project Structure



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

1. **Clone the repository:**
```bash
git clone https://github.com/whyshivansh/reelspro.git
cd reelspro
npm install


Create .env.local and add:
MONGODB_URI=your_mongodb_connection
NEXTAUTH_SECRET=your_secret_key
NEXTAUTH_URL=http://localhost:3000

IMAGEKIT_PUBLIC_KEY=your_imagekit_public
IMAGEKIT_PRIVATE_KEY=your_imagekit_private
IMAGEKIT_URL_ENDPOINT=https://ik.imagekit.io/your_id/


npm run dev




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

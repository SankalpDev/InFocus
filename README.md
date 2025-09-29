
# 📸 InFocus - A Modern Photo Sharing Platform

**InFocus** is a full-stack, modern photo sharing application built with the **Next.js App Router**. It allows users to sign in, share their moments, and interact with a community of users through posts, likes, and comments.

🔗 **Live Demo**: [InFocus](https://in-focus-delta.vercel.app/)
<img width="1919" height="855" alt="image" src="https://github.com/user-attachments/assets/4c9bd315-2416-4229-a6dd-f1cc9a85b6d7" />

---

## 🚀 Features

* 🔑 **Google Authentication** – Secure and easy sign-in using NextAuth.js
* 🖼️ **Create & Share Posts** – Upload images and add descriptions to share your moments
* ❤️ **Interactive Feed** – Like, comment on, and bookmark posts from users you follow
* 👤 **User Profiles** – Customizable profiles with avatars, bios, and personal post grid
* ➕ **Follow System** – Follow/unfollow users to personalize your feed
* 🔍 **Explore & Search** – Discover new content and search for users/posts
* 🌐 **Decentralized Storage** – Images stored on **IPFS** via **Pinata**
* 📱 **Responsive Design** – Works beautifully on both desktop & mobile

---

## 🛠️ Tech Stack

* **Framework:** [Next.js (App Router)](https://nextjs.org/)
* **Language:** TypeScript
* **Styling:** Tailwind CSS, Radix UI Themes
* **Authentication:** NextAuth.js
* **Database:** MongoDB
* **ORM:** Prisma
* **File Storage:** IPFS via Pinata
* **Deployment:** Vercel

---

## ⚙️ Getting Started

Follow these steps to set up the project locally:

### ✅ Prerequisites

* [Node.js](https://nodejs.org/) (v18.17 or later)
* [Git](https://git-scm.com/)

### 📥 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/SankalpDev/InFocus.git
   cd InFocus
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a file named `.env.local` in the root of your project and add the following:

   ```bash
   # MongoDB Database Connection String
   DATABASE_URL="your_mongodb_connection_string"

   # Pinata JWT for IPFS uploads
   PINATA_JWT="your_pinata_jwt"

   # NextAuth.js Configuration
   AUTH_SECRET="your_nextauth_secret"
   AUTH_GOOGLE_ID="your_google_client_id"
   AUTH_GOOGLE_SECRET="your_google_client_secret"

   # Required for NextAuth.js in development
   NEXTAUTH_URL="http://localhost:3000"
   ```

   🔑 Generate a NextAuth secret with:

   ```bash
   openssl rand -hex 32
   ```

4. **Generate the Prisma client**

   ```bash
   npx prisma generate
   ```

5. **Run the development server**

   ```bash
   npm run dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser 🎉

---

## 📦 Deployment

This project is deployed with **Vercel**.
Refer to the official deployment guide for instructions on how to configure Google OAuth and Pinata credentials.

---

## 📜 License

Distributed under the **MIT License**.
See [`LICENSE`](./LICENSE) for more information.

---

## 📬 Contact

👤 **Sankalp** – [@SankalpDev](https://github.com/SankalpDev)
📂 **Project Link:** [InFocus on GitHub](https://github.com/SankalpDev/InFocus)



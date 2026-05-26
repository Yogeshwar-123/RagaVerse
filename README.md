# RagaVerse 

**RagaVerse** is a futuristic, AI-powered, multi-lingual Indian music streaming and creator platform supporting songs across all Indian languages and eras—from classics to trending hits.

- Listen, sing, record, upload, and discover music like never before.
- Leverage AI for music creation and personalized recommendations.
- Supports artists, creators, and listeners in a seamless, premium experience.

## Tech Stack

- **Frontend:** Next.js 15, React, TypeScript, Tailwind CSS, Framer Motion, ShadCN UI
- **Backend:** Node.js, Express.js/Next.js API
- **Database:** PostgreSQL (+ Prisma ORM)
- **Authentication:** Google, GitHub, Email/OTP
- **Features:** AI Studio, Music Player, Playlists, Artist Dashboard, Admin Panel, SEO, Security

### Getting Started

1. Install dependencies:
   ```bash
   pnpm install
   # or
   npm install
   ```

2. Setup environment variables:
   Copy `.env.example` -> `.env` and fill your secrets.

3. Setup database:
   ```bash
   npx prisma migrate dev
   ```

4. Run locally:
   ```
   cd apps/web
   npm run dev
   ```

---

Full documentation in `/docs/` and deployment guide below.

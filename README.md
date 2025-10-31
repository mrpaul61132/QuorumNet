# QuorumNet
Citizen resporting platform for corruption and misconduct.
# QuorumNet

QuorumNet is a civic reporting platform where citizens can submit incidents, attach evidence, and engage in public moderation to surface truth and accountability. Inspired by *The Samaritan*, it blends community oversight with digital tools for transparency.

## Features (MVP)
- Submit reports with title, description, and attachments
- Browse public feed of reports
- Comment and upvote
- Moderator dashboard for verification
- Anonymous reporting with safety controls

## Tech Stack
- Frontend: Next.js (React)
- Backend: Vercel API routes + Supabase
- Database: PostgreSQL (via Supabase)
- Storage: Supabase Storage or S3
- Auth: Supabase Auth (optional)

## Getting Started
```bash
git clone https://github.com/<your-username>/QuorumNet.git
cd QuorumNet
npm install
npm run dev

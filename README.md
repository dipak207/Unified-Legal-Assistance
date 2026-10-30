# Unified Legal Assistance

Unified legal assistance platform combining Legal Query, Judgment Analysis, Layman Summarization, translation, and Family Law Assistant in one Next.js frontend.

## Architecture
- `vercel_frontend/`: unified Next.js frontend
- `backend/`: Legal Assistance FastAPI service
- AI/model services and supporting workflows remain in their existing directories
- Family Law API remains an independently deployed backend; configure its URL in the frontend environment

## Setup
See `GITHUB_SETUP.md`, `HANDOVER.md`, `RUN_STATUS.md`, and `vercel_frontend/FRONTEND_REDESIGN_NOTES.md`.

Never commit `.env` files, API keys, database credentials, or production secrets.

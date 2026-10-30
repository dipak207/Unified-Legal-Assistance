# Unified Legal Assistance

This repository is the new home for the unified Legal Assistance + Family Law Assistant project.

## Upload status

The repository and `feature/unified-legal-assistance-ui` branch are initialized. The complete application source tree is **not yet present** in this branch. The full source bundle and a Windows push helper are provided separately in the conversation download `ai-legal-assistance-unified-ready.zip`.

## Intended architecture
- `vercel_frontend/`: unified Next.js frontend
- `backend/`: existing Legal Assistance FastAPI service
- Family Law API remains an independently deployed FastAPI backend initially

## Safety
Never commit real `.env` files, API keys, database credentials, private keys, model weights, or production secrets. Keep `.env.example` files only.

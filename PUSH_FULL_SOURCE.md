# Push the complete source bundle

The repository currently contains bootstrap documentation; the full application tree is not uploaded yet.

## Windows (recommended)
1. Download and extract `ai-legal-assistance-unified-ready.zip` from the ChatGPT conversation.
2. Open the extracted `ai-legal-assistance-unified` directory.
3. Double-click `PUSH_TO_GITHUB.bat` (or run `./PUSH_TO_GITHUB.ps1` in PowerShell).
4. Sign in through Git Credential Manager when prompted.
5. The script clones `feature/unified-legal-assistance-ui`, copies the complete source tree, removes real environment/private-key files, commits, and pushes to that branch. It does not modify `main`.

Requirements: Git for Windows. Node.js/npm are required only if choosing the optional local frontend run at the end of the script.

Do not commit real `.env` files, API keys, database credentials, private keys, or other secrets. `.env.example` files are safe templates.

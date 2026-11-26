# No personal information in commits

This is a **public repository**. Never commit personal or sensitive information.

Do not commit:
- Names, email addresses, phone numbers, or home/physical addresses
- API keys, tokens, passwords, or any credentials (including GitHub tokens used for MCP)
- `.env` files or other local secrets/config
- Absolute local paths that reveal a username (e.g. `/home/<user>/...`)
- Private documents, client data, or anything not meant to be public

Before every commit:
- Review `git status` and `git diff --staged` for anything above
- Keep secrets in untracked, gitignored files or environment variables
- If something sensitive is committed by mistake, stop and flag it. Rotate the secret; do not just delete it in a later commit

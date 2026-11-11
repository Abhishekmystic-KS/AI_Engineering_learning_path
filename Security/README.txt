SECURITY AND SECRET MANAGEMENT

This folder explains how to protect API keys, passwords, tokens, and other private configuration.

FILES

1. env-and-gitignore.txt
2. api-key-security.txt
3. production-secrets.txt
4. security-files-to-remember.txt
5. security-checklist.txt

GOLDEN RULE

Never commit a real API key, password, private certificate, or production secret to Git.

If a secret is exposed, revoke or rotate it immediately. Deleting the file later does not remove it from Git history.
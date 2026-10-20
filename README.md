# Rich Life Ledger

A private personal finance tracker in the spirit of Monarch Money, built around the
Conscious Spending Plan from Ramit Sethi's *I Will Teach You to Be Rich*.

- **Encrypted**: all data is encrypted in the browser with AES-256-GCM. The key is derived
  from your passphrase (PBKDF2-SHA256, 600,000 iterations) and is never stored or sent.
- **Synced**: when opened as a claude.ai artifact, the encrypted vault is saved in your
  private per-user storage so it opens on any signed-in device. Only ciphertext leaves the browser.
- **Auto-lock** after 10 minutes idle. Encrypted backups can be downloaded and restored.
- **Features**: net worth, monthly cash flow, bank CSV import with auto-categorization that
  learns merchants, Conscious Spending Plan check against Ramit's ranges, savings goals,
  and manual accounts.

Ramit Sethi's ideas are paraphrased with chapter references. Not affiliated with him;
not financial advice.

`index.html` is written in artifact page format (the platform adds the `<!doctype>` wrapper on publish).

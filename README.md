{
  "filename": "README.md",
  "content": "# 🧷 Vault Backup Credential Restore [DO_NOT_PUSH]\n\n📦 Credentials recovered from failed `vault restore` job inside CI container (`/backup/vault-env.tgz`). Appears to contain production stack access keys.\n\n## 🧨 Contents\n- `.env.vault` (Live CI/CD keys)\n- `id_rsa` (Git deploy key)\n- `pgp.asc` (GPG backup key export)\n- `init.js` (boot context log)\n\n## 📡 Logging Node\nhttps://ghostline-drift-mirror.netlify.app/?source=vault-leak\n\nAll unauthorized access events are traced and logged."
}

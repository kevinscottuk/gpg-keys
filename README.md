## 🔐 GPG Public Key

This repository contains my public GPG key used to sign Git commits and releases.

### Fingerprint

    CA74 A2D4 4B9D 7F58 C383 9962 21CA F347 F88F 2E11

> ⚠️ Always verify the fingerprint before trusting this key.

---

### 📥 Import the Key

Download and import the key:

```bash
gpg --import kevin-scott.asc
```
---

### 🔍 Verify the Fingerprint

After importing, confirm the fingerprint matches:

```bash
gpg --fingerprint F88F2E11
```

---

### ✅ Verifying Signed Commits

Once the key is imported and trusted, you can verify commits:

```bash
git log --show-signature
```

---

### 🛡️ Trust Model

This key is published via:

- This repository (canonical source)
- My GitHub profile

You should verify the fingerprint via at least one independent channel before assigning trust.

---

### 📄 File

- `kevinscottuk.asc` — ASCII-armoured public key

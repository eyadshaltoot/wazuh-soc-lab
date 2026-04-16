# Detection & Analysis

## Detected Events

* Suspicious PowerShell execution detected
* Executable file created in Windows system directory
* Registry modification for persistence

---

## MITRE ATT&CK Mapping

* T1105 – Ingress Tool Transfer (File Download)
* T1574 – Persistence via DLL Hijacking

---

## Severity Assessment

**Severity: High**

**Reason:**
Multiple suspicious activities were detected including command execution, file drop, and persistence mechanisms, indicating a potential multi-stage attack.

---

## Conclusion

The attack simulation demonstrated how a malicious actor can execute commands, drop files, and establish persistence on a system. Wazuh successfully detected and correlated these activities into meaningful alerts.

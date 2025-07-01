# 🛠️ Wireshark Traffic Analysis Report

## 📁 Task Summary

This report documents network traffic captured using Wireshark after browsing to two websites (`google.com` and `poki.com`). The goal was to analyze live internet traffic and identify protocol-level interactions.

---

## ✅ Tools Used

- **Wireshark** (Network Protocol Analyzer)
- **Browser** (Chrome/Edge/Firefox)
- **Command Prompt / Terminal (Optional for ping)**

---

## 🌐 Task Steps Performed

1. Installed and launched Wireshark.
2. Selected the active network interface (Wi-Fi).
3. Started packet capture.
4. Browsed to:
   - [https://www.google.com](https://www.google.com)
   - [https://www.poki.com](https://www.poki.com)
5. Stopped the capture after 1 minute.
6. Applied filters to analyze specific domain-related traffic.
7. Exported `.pcapng` file and captured screenshots.
8. Identified at least 3 protocols and examined packet details.

---

## 📊 Protocols Identified

| Protocol     | Purpose                             |
|--------------|-------------------------------------|
| TCP          | Transport layer communication       |
| TLSv1.3      | Secure HTTPS connections            |
| DNS (Implied) | Domain resolution before HTTPS      |

---


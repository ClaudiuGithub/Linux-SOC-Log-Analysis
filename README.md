# Linux SOC Log Analysis

Basic SOC log analysis project using Kali Linux and journalctl.

This project demonstrates beginner-level SOC analyst skills by investigating Linux system logs, filtering authentication-related events, and identifying suspicious activity using command-line tools.

---

# Skills Used

- Linux terminal
- Log analysis
- journalctl
- grep
- Event filtering
- Basic incident investigation
- Log extraction

---

# Environment

- Kali Linux
- VirtualBox

---

# Commands Used

```bash
sudo journalctl | grep "password"

sudo journalctl | grep "Failed"

sudo journalctl | grep "error"

sudo journalctl | grep "Failed" > failed_logs.txt
```

---

# Password Related Events

The following command was used to identify password-related events inside Linux system logs.

```bash
sudo journalctl | grep "password"
```

![Password Logs](https://github.com/user-attachments/assets/37e6273f-00dd-43a7-973b-8f5c4e36c296)

This output shows authentication and password-related log entries extracted from Linux journal logs. The analysis demonstrates basic monitoring of authentication activity and credential-related system events.

---

# Failed Authentication Events

The following command was used to detect failed authentication and failed system-related events.

```bash
sudo journalctl | grep "Failed"
```

![Failed Logs](https://github.com/user-attachments/assets/323eaec0-0d06-49f9-ab38-a56e1d2de686)

This analysis helps identify suspicious login failures, failed operations, and potential brute-force activity by filtering failed events from Linux system logs.

---

# Error Event Analysis

The following command was used to search for error-related system events.

```bash
sudo journalctl | grep "error"
```

![Error Logs](https://github.com/user-attachments/assets/1f379fe0-a9a4-4eb1-885e-38e33ab122c8)

This output demonstrates basic event monitoring and troubleshooting techniques used in SOC environments. The analysis helps identify service issues, desktop environment problems, and system-related errors.

---

# Exporting Failed Logs to File

The following command was used to export failed and suspicious log events into a separate text file for later investigation.

```bash
sudo journalctl | grep "Failed" > failed_logs.txt
```

![Failed Logs TXT](https://github.com/user-attachments/assets/cd251a50-9316-474a-b439-a68d203f3b89)

This output demonstrates how failed system events can be extracted from Linux journal logs and stored inside a dedicated file for incident investigation and documentation purposes.

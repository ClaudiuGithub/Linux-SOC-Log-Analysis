# Commands Used

```bash
sudo journalctl | grep "password"

sudo journalctl | grep "Failed"

sudo journalctl | grep "error"

sudo journalctl | grep "Failed" > failed_logs.txt
```

---

# Password Related Events

This output shows authentication and password-related log entries extracted from the Linux journal logs.

![Password Logs](https://github.com/user-attachments/assets/37e6273f-00dd-43a7-973b-8f5c4e36c296)

---

# Failed Authentication Events

This analysis helps identify suspicious login failures and possible brute-force activity.

![Failed Logs](https://github.com/user-attachments/assets/323eaec0-0d06-49f9-ab38-a56e1d2de686)

---

# Error Event Analysis

The following command was used to search for system error messages. This output demonstrates basic event monitoring and troubleshooting techniques used in SOC environments.

![Error Logs](https://github.com/user-attachments/assets/1f379fe0-a9a4-4eb1-885e-38e33ab122c8)

---

# Exporting Failed Logs to File

This demonstrates basic log extraction and incident documentation techniques commonly used in SOC environments.

![Failed Logs TXT](https://github.com/user-attachments/assets/cd251a50-9316-474a-b439-a68d203f3b89)


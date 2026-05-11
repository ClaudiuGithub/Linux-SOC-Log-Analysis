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
<img width="1536" height="862" alt="password_log_analysis" src="https://github.com/user-attachments/assets/37e6273f-00dd-43a7-973b-8f5c4e36c296" />
This output shows authentication and password-related log entries extracted from the Linux journal logs.
<img width="1020" height="227" alt="Failed_log_analysis" src="https://github.com/user-attachments/assets/323eaec0-0d06-49f9-ab38-a56e1d2de686" />
This analysis helps identify suspicious login failures and possible brute-force activity.
<img width="1015" height="330" alt="error_log_analysis" src="https://github.com/user-attachments/assets/1f379fe0-a9a4-4eb1-885e-38e33ab122c8" />
The following command was used to search for system error messages. This output demonstrates basic event monitoring and troubleshooting techniques used in SOC environments.
<img width="1020" height="227" alt="Failed_log_analysis" src="https://github.com/user-attachments/assets/cd251a50-9316-474a-b439-a68d203f3b89" />
This demonstrates basic log extraction and incident documentation techniques commonly used in SOC environments.



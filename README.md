A modular suite of Bash scripts designed for Linux systems to automate routine maintenance tasks, including system backups, updates, cleanup, and log monitoring.

📌 This project is part of Assignment 5 (LinuxOS + LSP).

✅ Features
1. **Backup Script**

 Compresses selected user folders

Stores timestamped *.tar.gz backups in backups/

 Logs activity in logs/script_logs.txt

2. **System Update & Cleanup Script**

Runs:

apt update
apt upgrade
autoremove
autoclean


 Helps maintain system integrity

 Logs all output

3. **Log Monitoring Script**

 Monitors /var/log/syslog & /var/log/auth.log in real time

 Detects patterns (configurable in log_monitor.conf)

Alerts stored in script_logs.txt

Optional email alerts using mail command

4. **Maintenance Menu**

Interactive menu to run all tools from one place:

1) Run Backup
2) Perform System Update & Cleanup
3) Start Log Monitor (live)
4) View Script Logs
5) Exit

⚙️ Installation & Setup
1. Make scripts executable
cd scripts
chmod +x *.sh

2. Run the maintenance menu
cd Assignment5/scripts
./maintenance_menu.sh

   

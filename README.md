# BASH SCRIPTING SUITE FOR SYSTEM MAINTENANCE

A modular suite of Bash scripts designed for Linux systems to automate routine maintenance tasks such as system backups, updates, cleanup, and log monitoring.

PART OF ASSIGNMENT 5 (LINUXOS + LSP)

# ✅ FEATURES
## 1) BACKUP SCRIPT

COMPRESSES selected user folders

Saves timestamped .tar.gz backups to backups/

LOGS ACTIVITY to logs/script_logs.txt

Ensures reliable & consistent folder backup automation

## 2) SYSTEM UPDATE & CLEANUP SCRIPT

Runs essential system maintenance commands:

apt update
apt upgrade
autoremove
autoclean

MAINTAINS SYSTEM HEALTH

IMPROVES PERFORMANCE & SECURITY

LOGS ALL OUTPUT for review

## 3. **Log Monitoring Script**

 Monitors /var/log/syslog & /var/log/auth.log in real time

 Detects patterns (configurable in log_monitor.conf)

Alerts stored in script_logs.txt

Optional email alerts using mail command

## 4. **Maintenance Menu**

Interactive menu to run all tools from one place:

1) Run Backup
2) Perform System Update & Cleanup
3) Start Log Monitor (live)
4) View Script Logs
5) Exit

# ✅ Installation & Setup
## 1. Make scripts executable

### 1. Make scripts executable

From inside the scripts folder:

```bash
cd scripts
chmod +x *.sh

cd Assignment5/scripts
./maintenance_menu.sh

1) Run Backup
2) Perform System Update & Cleanup
3) Start Log Monitor (live)
4) View Script Logs
5) Exit


   

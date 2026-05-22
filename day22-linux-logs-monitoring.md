# Day 22 – Linux Logs, Monitoring & Troubleshooting

# Logs

Logs are records of system activity.

Used for:
- debugging
- troubleshooting
- monitoring
- security

---

# Log Directory

Most logs stored in:
/var/log

---

# Common Logs

syslog → system activity  
auth.log → login/authentication  
kern.log → kernel logs  
boot.log → boot logs  

---

# less Command

Used to read large files.

Example:
less /var/log/syslog

Exit:
q

---

# tail Command

View last lines:

tail /var/log/syslog

Live monitoring:
tail -f /var/log/syslog

---

# journalctl

Used for centralized system logs.

Examples:
journalctl
journalctl -n 20
journalctl -f

---

# top Command

Real-time system monitoring.

Shows:
- CPU usage
- RAM usage
- processes

---

# free Command

Check memory usage:

free -h

---

# uptime Command

Check:
- uptime
- system load

---

# Troubleshooting Workflow

Problem
↓
Check logs
↓
Check services/processes
↓
Identify issue
↓
Fix problem

---

# Key Learnings

- logs record system activity
- monitoring tracks system health
- troubleshooting depends on logs
- top monitors processes/resources
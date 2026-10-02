# Linux Administration & Networking Screenshots

A comprehensive repository documenting hands-on Linux system administration, filesystem management, permissions, resource monitoring, and network diagnostics tasks.

---

## 1. System Administration & Core Commands

Covers filesystem operations, permissions, file redirection, system statistics, and process monitoring.

| File | Description |
| :--- | :--- |
| [`01-linux-file-management-ls-mkdir-rm.png`](screenshots/01-linux-file-management-ls-mkdir-rm.png) | File and directory operations (`ls`, `mkdir`, `touch`, `rm`) in the user workspace |
| [`02-tail-var-log-syslog-monitoring.png`](screenshots/02-tail-var-log-syslog-monitoring.png) | Real-time system log monitoring using `tail -f` and `tail -5` on `/var/log/syslog` |
| [`03-directory-creation-and-rmdir-practice.png`](screenshots/03-directory-creation-and-rmdir-practice.png) | Directory management, folder creation, and recursive directory removal (`rm -rf`) |
| [`04-file-redirection-mv-echo-cat.png`](screenshots/04-file-redirection-mv-echo-cat.png) | File renaming (`mv`), stdout overwrite (`>`), and line appending (`>>`) |
| [`05-system-info-uname-df-du.png`](screenshots/05-system-info-uname-df-du.png) | Inspecting hostname, kernel details (`uname -a`), disk free (`df -h`), and directory sizes (`du`) |
| [`06-chmod-permissions-octal-modes.png`](screenshots/06-chmod-permissions-octal-modes.png) | Modifying file permissions using octal modes (`chmod 400`, `644`, `600`) |
| [`07-chmod-executable-and-chown-ownership.png`](screenshots/07-chmod-executable-and-chown-ownership.png) | Setting executable permissions (`chmod 755`) and changing ownership (`chown root:root`) |
| [`08-top-process-system-resource-monitor.png`](screenshots/08-top-process-system-resource-monitor.png) | Real-time process monitoring and system resource statistics using `top` |
| [`09-ps-process-list-and-kill-command.png`](screenshots/09-ps-process-list-and-kill-command.png) | Listing active terminal processes via `ps` and checking `kill` command syntax |
| [`10-ping-google-latency-and-packet-count.png`](screenshots/10-ping-google-latency-and-packet-count.png) | Testing ICMP network reachability and round-trip time with `ping` and `ping -c 4` |

---

## 2. Networking & Diagnostics

Covers DNS resolution, port testing, socket states, and network interface configurations.

| File | Description |
| :--- | :--- |
| [`01-telnet-and-dig-google.png`](screenshots/01-telnet-and-dig-google.png) | Testing HTTP port 80 connectivity via `telnet` and querying DNS records using `dig` |
| [`02-nslookup-google-dns-records.png`](screenshots/02-nslookup-google-dns-records.png) | Querying IPv4/IPv6 addresses via `nslookup` using DNS resolver `8.8.8.8` |
| [`03-ifconfig-network-interfaces-and-ip-help.png`](screenshots/03-ifconfig-network-interfaces-and-ip-help.png) | Inspecting network interfaces (`docker0`, `enp1s0`, `lo`) and `ip` command syntax guide |
| [`04-netstat-active-connections-and-sockets.png`](screenshots/04-netstat-active-connections-and-sockets.png) | Inspecting active internet connections and UNIX domain sockets using `netstat` |
| [`05-ss-socket-statistics.png`](screenshots/05-ss-socket-statistics.png) | Analyzing established connections and socket statistics using the `ss` utility |
| [`06-ifconfig-and-ip-subcommands.png`](screenshots/06-ifconfig-and-ip-subcommands.png) | Reviewing detailed interface configurations and `ip` subcommand parameter options |

---

## Summary of Commands Covered

* **Filesystem & I/O:** `ls`, `mkdir`, `touch`, `rm`, `mv`, `cat`, `echo`, `>`, `>>`
* **Access & Permissions:** `chmod`, `chown`
* **System & Storage:** `hostname`, `uname`, `df`, `du`, `top`, `ps`, `kill`
* **Logs & Monitoring:** `tail -f`, `tail -n`
* **Network & DNS:** `ping`, `telnet`, `dig`, `nslookup`, `ifconfig`, `ip`, `netstat`, `ss`

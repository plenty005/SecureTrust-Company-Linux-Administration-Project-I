# SecureTrust Company - Linux Administration Project I 
Ubuntu/Debian/Kali Server Administration project demonstrating SSH hardening, UFW firewall configuration, Linux users & groups management, directory permissions, and SGID bit setup.
## Hardening & Workflows Implemented 
**Custom SSH Port:** Direct `root` login disabled; key-based access configured.
**SSH Hardening:** Direct`root` login disabled; key-based access configured.
**Custom SSH port:** Socket-activated SSH on TCP port `2222`. 
**Collabotative Workspace:** `/var/projects/sec-workspace` configured with `SGID` bit (`2770`) for group `sec-team`.
**Umask Configuration:** User environments configured with `umask 002` for shared read/write access (`-rw-rw-r--`).
**Firewall Rules:** UFW enabled, allowing only port `2222/tcp`.

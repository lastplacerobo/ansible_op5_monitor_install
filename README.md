# Playbook for basic installation of OP5 Monitor
Simple playbook to install OP5 Monitor from repos. Needs Centos7/RHEL7 server running. Selinux in enforcing but OP5 Monitor services running unconfined.

Repos required:
* CentOS-7 - Base 
* Extra Packages for Enterprise Linux 7 - x86_64 - Epel 
* op5-monitor-updates/7/x86_64 - op5 Monitor Updates 

OP5s public repo: http://repos.op5.com/el7/x86_64/monitor/8/updates/

Selinux conf: https://support.itrsgroup.com/hc/en-us/articles/360023683114-How-to-configure-OP5-Monitor-with-SELinux-enforcing

"op5-release" RPM contains the op5 repository configuration and RPM GPG key

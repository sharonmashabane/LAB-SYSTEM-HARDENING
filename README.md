# LAB-SYSTEM-HARDENING
SYSTEM HARDENING
What I Did to Complete the System Hardening Lab

Logged into the EC2 Instance

Accessed my Amazon Linux instance using SSH.

Applied System Updates

Ran update commands (yum update / apt update) to install the latest security patches.

Checked and Disabled Unnecessary Services

Used systemctl to list services.

Stopped and disabled services that were not required (reducing attack surface).

Configured Firewall and Security Groups

Allowed only essential traffic (e.g., SSH on port 22, HTTP/HTTPS if needed).

Blocked unused ports with firewall rules.

Reviewed User Accounts and Permissions

Removed or disabled unused accounts.

Enforced strong password policies.

Checked file and directory permissions (chmod, chown).

Enabled Logging and Monitoring

Verified system logs were active.

Connected instance logs to CloudWatch for monitoring.

Tested Security

Tried connecting from restricted ports to confirm access was blocked.

Validated that only authorized users could log in.

![LAB SYSTEM HARDENING](https://github.com/user-attachments/assets/11da4971-9810-425d-bdfd-d7a361c0d720)



















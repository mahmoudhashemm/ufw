البروتات المستخدمة 
```
ss -tulpn
```
البروتات الى محتاج افتحها 
```
sudo ufw allow 22/tcp      # SSH
sudo ufw allow 53          # DNS
sudo ufw allow 1194/udp    # VPN
sudo ufw allow 25/tcp      # SMTP
sudo ufw allow 465/tcp     # SMTPS
sudo ufw allow 587/tcp     # Submission
sudo ufw allow 143/tcp     # IMAP
sudo ufw allow 993/tcp     # IMAPS
sudo ufw allow 110/tcp     # POP3
sudo ufw allow 995/tcp     # POP3S
sudo ufw allow 4190/tcp    # Sieve
sudo ufw allow 80/tcp      # HTTP
sudo ufw allow 443/tcp     # HTTPS
sudo ufw allow 8080/tcp
sudo ufw allow 8443/tcp
sudo ufw allow 9443/tcp
sudo ufw allow 943/tcp
sudo ufw allow 8505/tcp
sudo ufw allow 9505/tcp
sudo ufw allow 8205/tcp
sudo ufw allow 9001/tcp
```

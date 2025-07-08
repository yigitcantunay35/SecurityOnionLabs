## CASE 1
## Amaç: Security Onion IDS motorlarının (Zeek / Suricata) saldırı trafiğini algılayıp loglaması.

### 1.Kendi local ağımızda kali üzerinden saldırı yaparak bu logları incelemek ve çıktılarını yorumlayarak çıakrımlar yapmaktır.

### Uygulama Adımları:

'nmap -sS -p- 192.168.1.X'

'https://<security_onion_ip>'

'alert.signature : "*Nmap*" veya alert.severity:1'

![image](https://github.com/user-attachments/assets/5fded5c8-ffec-4d3d-8bb0-7c97b07cd77c)

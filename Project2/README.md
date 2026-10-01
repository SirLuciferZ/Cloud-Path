## Info
this is the beginning of my networking project.
in this project im gonna document everything that I've learned during the networking courses.

### Part 1
i found the default gateway of my router. it was `192.168.1.1`
i entered this ip into my browser and logged in to my router's management page.
inside that page, i could find the mac address, subnet mask and the dns that was set on my router.
also, i found all the attached devices that are connected to the router.

### Part 2
I learned subnetting. in companies, subnetting is a non-negotiable topic. because before subnetting, everything is a one giant network that each client can talk to eachother.
when we do subnetting, we divide the public networks like guest clients from private networks like databases.
i used an IP subnet calculator to get 4 subnets. it gave their `Network Address`,	`Usable Host Range` and	`Broadcast Address`.
after some research, i found out that as a cloud engineer, i should do subnetting.
usually, we divide it into 4 subnets. 2 for public and 2 for private networks. we divide them into 2 different zones. like `A` and `B` and put 1 public and 1 private network inside each zone.
this is because if a zone fails, the other zone can handle both public and private networks.

These are the submasks for my network:
| Network Address | Usable Host Range | Broadcast Address |
|---|---|---|
| 192.168.1.0 | 192.168.1.1 - 192.168.1.62 | 192.168.1.63 |
| 192.168.1.64 | 192.168.1.65 - 192.168.1.126 | 192.168.1.127 |
| 192.168.1.128 | 192.168.1.129 - 192.168.1.190 | 192.168.1.191 |
| 192.168.1.192 | 192.168.1.193 - 192.168.1.254 | 192.168.1.255 |

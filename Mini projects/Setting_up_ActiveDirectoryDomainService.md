In this project, I have Installed and set up a Active Directory server on my Windows 2025 Server VM. I have create a new user and new security group and added the user into the security group. Finally, I have verified the if created new user was able to login using my Windows 11 VM.

1) Installing and setting up an Active Directory Domain Services (AD DS) Server:

https://github.com/user-attachments/assets/350f1e3b-ec02-4be3-bc31-ff4ddfd50ebb

2) Adding a new user and security group. And adding the new user in the security group.

https://github.com/user-attachments/assets/499817da-b55b-47cf-a354-04444e50bcd9

3) Verifying I can login with the new user account.

https://github.com/user-attachments/assets/8d48b0bd-6db0-41ea-bb32-3ea29c614d75

Issue faced and how I solved it:

<img width="500" height="102" alt="image" src="https://github.com/user-attachments/assets/84b4eb47-bf89-4f92-b9c0-dd192745b21a" />

I got this error while setting up my AD DS server. I have made researched google about this error and found out I got this error because the server is getting a dynamic IP address from DHCP. To resolve this error the server needs to be allocated an static IP address, so client devices on the network can easily find the server everytime without any issues because of dynamically changing IP address. I also found out that the AD server should point out to itself to advoid relying on external DNS server and resolve all traffic locally, so I configured the DNS server with the same address as IP address. 

After these changes, I have solved this error.  




  #2









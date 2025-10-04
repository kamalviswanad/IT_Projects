In this project I have set up BitLocker on my Windows 11 VM.

Verifying if the VM has TPM enabled:

https://github.com/user-attachments/assets/9fa8fe9e-b496-497a-9af7-6ee0bda267d0

Setting up bitlocker. And verifying if it has configured correctly using cmd:

https://github.com/user-attachments/assets/0eaf4f9b-c32d-4829-8dc8-fb0685305fce

Issues face and how I fixed them:

1) <img width="718" height="554" alt="Screenshot 2025-10-04 133640" src="https://github.com/user-attachments/assets/98eee6ef-e6ce-4cb7-be6d-aa719da83519" />

I faced this issue ON my VM, even though I did not attach any bootable devices on my computer. After some research I found out that I got this issue because the ISO image is still attached to my VM even though I installed it on my VM a long time ago. So, I made a few changes to the VM's settings.

Before:  <img width="863" height="374" alt="Screenshot 2025-10-04 134036" src="https://github.com/user-attachments/assets/93be1a95-2221-4af7-b6ee-a58d729f5f27" />

After: <img width="874" height="341" alt="Screenshot 2025-10-04 134235" src="https://github.com/user-attachments/assets/d89e2ef5-d32d-40bb-b5bd-54d046d39f8d" />




                                                     





#4







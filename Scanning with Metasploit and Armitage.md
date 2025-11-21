# Scanning with Metasploit and Armitage

1. While in the Kali Linux VM, type in the following command in the Terminal: "service postgresql start".

<img width="533" height="28" alt="image" src="https://github.com/user-attachments/assets/109f31ae-ded4-41d0-9766-5676e2f92356" />

Result of Step 1

2. Type in the following command to view the folders and files: "ls".

<img width="888" height="250" alt="image" src="https://github.com/user-attachments/assets/8b3cc28c-5e3d-4312-9734-8d500772ee11" />

Result of Step 2

3. Then type the following command to view the contents of text file named sampleflag.txt: "more sampleflag.txt".

<img width="481" height="69" alt="image" src="https://github.com/user-attachments/assets/5f13441e-6687-4869-9b5c-e9fe9ed79783" />

Result of Step 3

4. After that type in the following command to switch to the Armitage directory: "cd armitage".

<img width="354" height="70" alt="image" src="https://github.com/user-attachments/assets/b769f5b5-caae-4316-8c6f-93ad239adfb6" />

Result of Step 4

5. Type in the following command to switch to the Metasploit interface: "msfconsole".

<img width="940" height="586" alt="image" src="https://github.com/user-attachments/assets/23307e5e-4e33-4311-907e-489a7312f48e" />

Result of Step 5

6. Now type in the following command to begin a database nmap scan: "msf > db_nmap 192.168.1.*". *Note this is subjec to take up to 5 minutes to complete. 

<img width="942" height="114" alt="image" src="https://github.com/user-attachments/assets/d91cc9f2-9dd9-479e-a087-f7688e115668" />

Result of Step 6

7. Now type in the following command to start Armitage: "./armitage".

<img width="773" height="465" alt="image" src="https://github.com/user-attachments/assets/3fbacf18-0446-48cc-b7ad-c2b265b5cff8" />

Result of Step 7

8. Then click connect and select yes to start Metasploit. 

9. Once Metasploit starts up. Right click on the window on the top to and go through the Auto Layout drop-down and selct Stack.

<img width="509" height="366" alt="image" src="https://github.com/user-attachments/assets/5d9f6217-02a4-44cd-8a42-b2717a5004f6" />

Result of Step 9

10. Right on the IP of 192.168.1.254 and select scan. *Note the complete scan can take up to 5 minutes.

<img width="308" height="239" alt="image" src="https://github.com/user-attachments/assets/b84b0800-3309-44a6-80fd-66c248b395e4" />

Result of Step 10

11. To do same as Step 10 for 192.168.1.30.

12. To do same as Step 10 for 192.168.1.20.

<img width="720" height="244" alt="image" src="https://github.com/user-attachments/assets/5111d26a-1810-4f79-b61c-d6e88ea2c257" />

Results from 11 to 12

# Password Cracking with John the Ripper and NetworkWalks Tools 
# Objectives
This exercise helps you learn how password cracking works and why it is important to use strong passwords for protection.

# Tools & Resources
| Tools | Purpose |
|--------| --------- |
|Johnny | Graphical Interface for running John the Ripper. |
| PDF Hash Extractor | Extracts password hashes from PDF files. |
| NetworkWalks Hash Calculator | Generates password hashes from PDF files. |
| NetworkWalks Password Cracker | Attempts to recover passwords from extracted hashes. |

# Procedure
# John the Ripper                         
### Step 1: Download and install the required software

What I did:
Downloaded and installed the John the Ripper and Johnny GUI software required for the password cracking exercise.

How I did it:
- Visited the official download website.
- Downloaded the required software.
- Followed the installation instructions.

Screenshots: </br>

<img width=400 height=300 alt="johnny_gui" src="https://github.com/user-attachments/assets/7720745a-2004-487c-ad8b-117abf0201db" />


### Step 2: Extract the PDF Hash
I downloaded the encrypted PDF file and uploaded it to a hash extractor website. After receiving the hash value, I saved it to my Notepad as a text file.

Screenshots: </br>

<img width=50% height="520" alt="hash_extractor" src="https://github.com/user-attachments/assets/261be994-7d44-4c0d-af18-5dd7cc362369" />


### Step 3: Perform the password-cracking exercise
I then opened Johnny and uploaded the text file containing the hash value, and executed the first command.

Screenshots: </br>

<img width=400 height="300" alt="comand_execution" src="https://github.com/user-attachments/assets/1c0b3be4-df71-4b17-9788-8d4a5e304bc0" />


### Step 4: Verify the results
The password was then successfully recovered, and I was able to open the PDF file.

Screenshots: </br>

<img width=400 height=300 alt="pdf1_password" src="https://github.com/user-attachments/assets/872ef28b-1074-4715-8ccb-b9df4bf57257" />

# NetworkWalks Tools
### Step 1: Download the files and open NetworkWalks Hash Calculator
I downloaded the locked PDF files from the NetworkWalks lab page. I then opened the NetworkWalks Hash Calculator in my web browser and uploaded the PDF file. The tool read the file and gave me the hash value.

Screenshots: </br>

<img width="400" height="300" alt="hash_calculator" src="https://github.com/user-attachments/assets/56bafe67-67c5-4171-a4bb-0b973954f5a8" />


### Step 2: Use Networkwalks Password Cracker
I copied the full hash value given to me and pasted it into the Password Cracker. I then uploaded the default password text file and started the attack.

Screenshots: </br>

<img width="400" height="300" alt="password_cracker" src="https://github.com/user-attachments/assets/55f386e7-6143-41d2-ac64-26d8a43fceba" />


### Step 3: Verify the results
Once finished. The cracked password was shown on the screen, and I was able to open the PDF file. I used the same method for the rest of the PDF files that needed to be opened.

Screenshots: </br>

<table>
  <tr>
    <td><img width="400" height="300" alt="pdf2_password" src="https://github.com/user-attachments/assets/34d7adc1-3b53-4327-94cd-d3710507b8eb" /></td>
    <td><img width="400" height="300" alt="pdf1_nwpassord" src="https://github.com/user-attachments/assets/b74e8a34-5476-45d3-ac28-8b156ae4295e" /></td>
    <td><img width="400" height="300" alt="pdf3_password" src="https://github.com/user-attachments/assets/28a97b24-3868-4edc-bcc5-4e67aacdd373" /></td>
  </tr>
</table>

# Conclusion
The practical exercise provided hands on experience in using the NetworkWalks tools as well as John the Ripper to perform password recovery. I successfully completed the required steps, from processing the input file to recovering the password.

This exercise helped me understand how password hashes are generated and used in password cracking processes, as well as how different tools work together to achieve the desired result.

# Author
Zyaan Makda
LinkedIn: https://linkedin.com/in/zyaan-career

# Disclaimer
This project is intended for educational purposes only. All tools and techniques demonstrated should only be used on files and systems that you own or have explicit permission to test. The author is not responsible for any misuse of the information provided.

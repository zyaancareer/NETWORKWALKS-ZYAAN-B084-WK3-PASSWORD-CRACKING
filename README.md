# Password Cracking With John the Ripper and NetworkWalks Tools 
# Objectives
This exercise helps you learn how password cracking works and why it is important to use strong passwords for protection.

# Tools & Resources
| Tools | Purpose |
|--------| --------- |
|Jonny GUI| Graphical Interface for running Jack the Ripper. |
| PDF Hash Extractor | Extracts password hashes from PDF files. |
| NetworkWalks Hash Calculator | Generates password hashes from PDF files. |
| Networkwalks Password Cracker | Attempts to recover passwords from extracted hashes. |

# Procedure
# John the Ripper                         
# Step 1: Download and install the required software

What I did:
Downloaded and installed the John the Ripper and Johnny GUI software required for the password cracking exercise.

How I did it:
- Visited the official download website.
- Downloaded the required software.
- Followed the installation instructions.

Screenshot: </br>

<img width=50% height="691" alt="johnny_gui" src="https://github.com/user-attachments/assets/7720745a-2004-487c-ad8b-117abf0201db" />


# Step 2: Download the required tool
I downloaded the encrypted PDF file and uploaded it to a hash extractor website. After receiving the hash value, I saved to to my notepad as a txt file.

Screenshot: </br>

<img width=50% height="520" alt="hash_extractor" src="https://github.com/user-attachments/assets/261be994-7d44-4c0d-af18-5dd7cc362369" />


# Step 3: Perform the password-cracking exercise
I then opened Johnny and uploaded the txt file containing the hash value and executed the first command.

Screenshot: </br>

<img width=50% height="689" alt="comand_execution" src="https://github.com/user-attachments/assets/1c0b3be4-df71-4b17-9788-8d4a5e304bc0" />


# Step 5: Verify the results
The password was then successfully recovered and I was able to open the PDF file.

Screenshot: </br>

<img width=50% height="769" alt="pdf1_password" src="https://github.com/user-attachments/assets/872ef28b-1074-4715-8ccb-b9df4bf57257" />

# NetworkWalk Tools
# Step 1: Download the files and open Networkwalks Hash Calculator
I downloaded the locked PDF files from the NetworkWalks lab page. I then opened the Networkwalks Hash Calculator in my web browser and uploaded the PDF file. The tool read the file and gave you the hash value.

Screenshot: </br>

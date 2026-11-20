# PDF Password Cracking Lab Using Networkwalks Tools

## 1. Introduction

This project demonstrates the process of recovering passwords from three password-protected PDF files using the online Networkwalks Hash Calculator and Networkwalks Password Cracker tools.

The practical lab was performed on a Linux operating system using a web browser. The objective was to understand PDF hash extraction, password recovery, and verification of recovered passwords.

## 2. Objectives

- Understand how password-protected PDF files work.
- Generate hashes from encrypted PDF files.
- Learn how PDF password hashes are used in password recovery.
- Use online password-cracking tools to attempt password recovery.
- Recover passwords for three encrypted PDF files.
- Verify the recovered passwords by opening the protected PDF documents.

## 3. Tools and Technologies Used

| Tool | Purpose |
|---|---|
| Linux (Ubuntu/Kali) | Operating system |
| Firefox / Google Chrome | Web browser |
| Networkwalks Hash Calculator | Generate PDF hashes |
| Networkwalks Password Cracker | Attempt password recovery |
| PDF Viewer | Verify recovered passwords |

### Online Resources

- Lab Page: https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/
- Hash Calculator: https://networkwalks.com/hash-calculator/
- Password Cracker: https://networkwalks.com/password-cracker/

## 4. Lab Methodology

The same password recovery process was performed on three different password-protected PDF files.

### Step 1: Download the Encrypted PDF Files

I downloaded the three encrypted PDF files provided for the lab and saved them to my Linux system.

### Step 2: Generate PDF Hashes

For each PDF file:

1. Opened the Networkwalks Hash Calculator.
2. Uploaded the encrypted PDF.
3. Allowed the tool to process the file.
4. Obtained the generated PDF hash beginning with `$pdf$`.
5. Copied the complete hash value.

This process was repeated for all three PDF files.

### Step 3: Submit Hashes to the Password Cracker

I opened the Networkwalks Password Cracker website.

For each PDF file, I:

1. Pasted its corresponding PDF hash.
2. Started the password recovery process.
3. Waited for the tool to attempt password recovery.
4. Recorded the recovered password when available.

### Step 4: Recover the Passwords

The Password Cracker attempted to identify matching passwords for the three supplied PDF hashes.

The recovered passwords were recorded separately for each PDF file.

### Step 5: Verify the Recovered Passwords

After recovering the passwords, I opened each encrypted PDF using my Linux PDF viewer.

I entered the corresponding recovered password for each document and verified that the PDFs opened successfully.

## 5. Results

The practical exercise involved three password-protected PDF files.

| PDF File | Hash Generated | Verification |
|---|---|---|
| PDF 1 | Yes | Done |
| PDF 2 | Yes | Done |
| PDF 3 | Yes | Done |

## 6. Screenshots / Evidence

The following screenshots document the practical work:

### PDF 1
- PDF file downloaded.
- Hash generated.
- Hash submitted to Password Cracker.
- Password recovery result.
- PDF successfully opened.
<img width="1366" height="728" alt="pdf1-hash-cracked" src="https://github.com/user-attachments/assets/2d0e1aee-b236-4220-ba13-989923da1fa4" />
<img width="1366" height="728" alt="pdf1-password" src="https://github.com/user-attachments/assets/4f9964e6-d168-4dc5-b969-117d6d7176d9" />
<img width="1366" height="728" alt="pdf1-successful" src="https://github.com/user-attachments/assets/69d31e37-4154-4d2a-a2f3-fd24ffcdc781" />

### PDF 2
- PDF file downloaded.
- Hash generated.
- Hash submitted to Password Cracker.
- Password recovery result.
- PDF successfully opened.
<img width="1366" height="728" alt="pdf2-hash-cracked" src="https://github.com/user-attachments/assets/46def695-0580-4d9c-90ae-35d1695b9801" />
<img width="1366" height="728" alt="pdf2-password" src="https://github.com/user-attachments/assets/dd25a5d1-c9ab-46fb-ad12-7a15757072aa" />
<img width="1366" height="728" alt="pdf-successful" src="https://github.com/user-attachments/assets/e654033c-c402-4136-b7a0-dffb054377bf" />

### PDF 3
- PDF file downloaded.
- Hash generated.
- Hash submitted to Password Cracker.
- Password recovery result.
- PDF successfully opened.
<img width="1366" height="728" alt="pdf3-hash-cracked" src="https://github.com/user-attachments/assets/6da1741c-671b-4b85-b45e-0d093f3d58ed" />
<img width="1366" height="728" alt="pdf3-password" src="https://github.com/user-attachments/assets/6209ba08-3cf0-436a-958f-a7771bc722f7" />
<img width="1366" height="728" alt="pdf3-successful" src="https://github.com/user-attachments/assets/f878ffac-f0a1-44d2-94ba-28770d6c1f90" />


## 7. Learning Outcomes

Through this practical lab, I learned:

- How password-protected PDF documents use cryptographic password verification.
- How to generate PDF hashes using an online hash calculator.
- How password-cracking tools attempt to recover passwords.
- How to perform password recovery using browser-based tools on Linux.
- How to verify recovered passwords by opening encrypted PDF documents.
- How to document cybersecurity practical exercises with screenshots.

## 8. Conclusion

This practical lab demonstrated the process of recovering passwords from three password-protected PDF files using Networkwalks online tools.

I generated individual hashes for all three PDF files, submitted them to the Password Cracker, attempted password recovery, and verified the recovered passwords by opening the corresponding documents.

The exercise provided practical knowledge of PDF password security, hash extraction, password recovery techniques, and the use of cybersecurity tools on Linux.

**Note:** This lab was performed for educational purposes using lab-provided PDF files. Password recovery should only be performed on files that you own or have permission to test.

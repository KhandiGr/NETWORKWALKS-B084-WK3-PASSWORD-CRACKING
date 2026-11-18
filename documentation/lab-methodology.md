# WK3 Lab Methodology

## 1. Password Cracking with JTR (Johnny)

### Objective
To use Johnny, the graphical interface for John the Ripper, to analyse a password-protected PDF hash and recover the password.

### Procedure
1. Install Johnny using the installation package provided.
2. Complete the installation and launch Johnny.
3. Open the settings and configure the path to `John.exe`.
4. Download the encrypted PDF provided for the lab.
5. Use an online PDF hash extractor to extract the encrypted PDF's hash.
6. Copy the extracted hash into Notepad.
7. Save the hash in a text file.
8. Open the saved hash file in Johnny.
9. Select the appropriate password-file format.
10. Start a new password-cracking attack.
11. Review the results and retrieve the recovered password.
12. Open the encrypted PDF using the recovered password to verify the result.

## 2. Password Cracking with Networkwalks Tools

### Objective
To use the Networkwalks Hash Calculator and Password Cracker to recover the password for an encrypted PDF.

### Procedure
1. Download the encrypted PDF provided for the lab.
2. Open the Networkwalks Hash Calculator.
3. Select the PDF upload option.
4. Upload the encrypted PDF and generate its hash.
5. Copy the generated hash.
6. Open the Networkwalks Password Cracker.
7. Paste the copied hash into the password-cracking tool.
8. Start the dictionary attack.
9. Monitor the cracking process.
10. Retrieve the recovered password when the attack is successful.
11. Open the encrypted PDF and enter the recovered password to verify access.

## Verification

For both exercises, successful password recovery was verified by using the recovered password to open the corresponding encrypted PDF.

## Conclusion

The lab provided practical experience with two password-cracking approaches: using Johnny with John the Ripper and using the Networkwalks password-cracking tools. Both exercises demonstrated the process of extracting password hashes, conducting password-recovery attempts, and verifying the recovered passwords.

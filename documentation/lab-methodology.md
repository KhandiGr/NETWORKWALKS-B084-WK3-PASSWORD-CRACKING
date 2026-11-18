# WK3 Lab Methodology

**Programme:** Networkwalks Cybersecurity Internship  
**Batch:** B084  
**Module:** WK3 – Password Cracking

This document outlines the procedures completed during the two password-recovery practical exercises. Screenshots are included as supporting evidence for each stage.

---

## 1. Password Cracking with JTR (Johnny)

### Objective

To use Johnny, the graphical interface for John the Ripper, to analyse a password-protected PDF hash and recover the password.

### Procedure

**Step 1: Install Johnny**

Install Johnny using the installation package provided. Complete the installation process and launch the application.

![Johnny installation folder](../screenshots/PM1-JTR/01-install-johnny-installation-folder.png)

![Select installation components](../screenshots/PM1-JTR/02-install-johnny-select-components.png)

![Start menu shortcuts](../screenshots/PM1-JTR/03-install-johnny-start-menu-shortcuts.png)

![Complete Johnny installation](../screenshots/PM1-JTR/04-install-johnny-complete-setup.png)

![Launch Johnny](../screenshots/PM1-JTR/05-launch-johnny-desktop-shortcut.png)

**Step 2: Configure Johnny**

Open Johnny's settings and browse for the `John.exe` executable. Select the executable to configure the application.

![Johnny main window](../screenshots/PM1-JTR/06-johnny-main-window.png)

![Browse for John executable](../screenshots/PM1-JTR/07-open-settings-browse-for-john-exe.png)

![Select John executable](../screenshots/PM1-JTR/08-select-john-exe.png)

**Step 3: Extract the PDF hash**

Open the online PDF hash extractor and select the encrypted PDF provided for the lab. Extract the hash and copy the generated value.

![Online PDF hash extractor](../screenshots/PM1-JTR/09-online-pdf-hash-extractor.png)

![Select encrypted PDF](../screenshots/PM1-JTR/10-select-encrypted-pdf-for-hash-extraction.png)

![Extract PDF hash](../screenshots/PM1-JTR/11-extract-pdf-hash.png)

![Copy extracted hash](../screenshots/PM1-JTR/12-copy-extracted-hash.png)

**Step 4: Save the extracted hash**

Open Notepad, paste the extracted hash, and save it as a text file for use in Johnny.

![Open Notepad](../screenshots/PM1-JTR/13-open-notepad.png)

![Paste hash into Notepad](../screenshots/PM1-JTR/14-paste-hash-into-notepad.png)

![Save hash file](../screenshots/PM1-JTR/15-save-hash-file.png)

![Locate saved hash file](../screenshots/PM1-JTR/16-locate-saved-hash-file.png)

**Step 5: Load the hash into Johnny**

Open the saved hash file in Johnny and select the appropriate password-file format.

![Open password file in Johnny](../screenshots/PM1-JTR/17-open-johnny-password-file.png)

![Select password file format](../screenshots/PM1-JTR/18-select-password-file-format.png)

![Select saved hash file](../screenshots/PM1-JTR/19-select-saved-hash-file.png)

**Step 6: Start the password-recovery attack**

Start a new attack in Johnny and review the results to retrieve the recovered password.

![Start new attack](../screenshots/PM1-JTR/20-start-new-attack.png)

![View recovered password](../screenshots/PM1-JTR/21-view-cracked-password-in-johnny.png)

**Step 7: Verify the recovered password**

Open the encrypted PDF and enter the recovered password to confirm that the document can be accessed.

![Open encrypted PDF with recovered password](../screenshots/PM1-JTR/22-open-encrypted-pdf-with-cracked-password.png)

![JTR captured flag](../screenshots/PM1-JTR/23-jtr-captured-flag.png)

---

## 2. Password Cracking with Networkwalks Tools

### Objective

To use the Networkwalks Hash Calculator and Password Cracker to recover the password for an encrypted PDF.

### Procedure

**Step 1: Download the encrypted PDF**

Download the encrypted PDF provided in the lab folder.

![Download encrypted PDF](../screenshots/PM2-NETWORKWALKS-TOOLS/01-download-encrypted-pdf-from-lab-folder.png)

**Step 2: Open the Networkwalks Hash Calculator**

Navigate to the Networkwalks Hash Calculator:

https://networkwalks.com/hash-calculator/

Select the PDF upload option.

![Open Networkwalks Hash Calculator](../screenshots/PM2-NETWORKWALKS-TOOLS/02-open-networkwalks-hash-calculator.png)

![Select PDF upload option](../screenshots/PM2-NETWORKWALKS-TOOLS/03-select-pdf-upload-tab.png)

**Step 3: Generate and copy the PDF hash**

Select and upload the encrypted PDF. Generate the hash and copy the resulting value.

![Select encrypted PDF file](../screenshots/PM2-NETWORKWALKS-TOOLS/04-select-encrypted-pdf-file.png)

![Copy generated PDF hash](../screenshots/PM2-NETWORKWALKS-TOOLS/05-copy-generated-pdf-hash.png)

**Step 4: Open the Networkwalks Password Cracker**

Open the Networkwalks Password Cracker and paste the copied PDF hash into the appropriate field.

![Open Networkwalks Password Cracker](../screenshots/PM2-NETWORKWALKS-TOOLS/06-open-networkwalks-password-cracker.png)

![Paste PDF hash](../screenshots/PM2-NETWORKWALKS-TOOLS/07-paste-pdf-hash.png)

**Step 5: Start and monitor the dictionary attack**

Start the dictionary-based password attack and monitor the cracking process.

![Start dictionary attack](../screenshots/PM2-NETWORKWALKS-TOOLS/08-start-dictionary-attack.png)

![Monitor cracking progress](../screenshots/PM2-NETWORKWALKS-TOOLS/09-monitor-cracking-progress.png)

**Step 6: Retrieve the recovered password**

Review the results and retrieve the password when the attack is successful.

![Password cracked successfully](../screenshots/PM2-NETWORKWALKS-TOOLS/10-password-cracked-successfully.png)

**Step 7: Verify the recovered password**

Open the encrypted PDF and enter the recovered password to verify access.

![Open locked PDF with recovered password](../screenshots/PM2-NETWORKWALKS-TOOLS/11-open-locked-pdf-enter-retrieved-password.png)

![Networkwalks captured flag](../screenshots/PM2-NETWORKWALKS-TOOLS/12-networkwalks-captured-flag.png)

---

## 3. Verification

For both practical exercises, password recovery was verified by entering the recovered password into the corresponding encrypted PDF and confirming that the document could be opened.

## 4. Conclusion

The WK3 practical exercises provided hands-on experience with two password-recovery approaches: John the Ripper through its Johnny graphical interface and the Networkwalks password-cracking tools.

The exercises demonstrated the process of extracting password hashes, preparing hash data, conducting dictionary-based password-recovery attempts, reviewing results, and verifying recovered passwords against encrypted PDF documents.

All activities were completed within the context of the authorised cybersecurity training lab. Password-cracking techniques should only be performed on files, systems, and data for which permission has been granted.

# Week 3 – Password Cracking Lab (WK3 PM1 + WK3 PM2)

This repository documents the Week 3 practical work using **John the Ripper** and the NetworkWalks hash/password-cracking tools. WK3 PM1 and WK3 PM2 are presented together in one repository.

> **Scope:** These activities were performed as a cybersecurity learning exercise on the provided lab PDF/hash material. Use password-auditing tools only on files and systems you own or are explicitly authorized to test.

## Practical Modules

### WK3 PM1 – John the Ripper

- Worked with the extracted PDF hash in John the Ripper.
- Observed the recovered password entry in the John the Ripper interface.
- Reviewed the results after the cracking process completed.
- Captured the application screenshots as evidence.

**Evidence screenshots**

| Screenshot | What it shows |
|---|---|
| `screenshots/HASH-1-CRACKED.png` | John the Ripper results view showing the recovered entry and remaining entries |
| `screenshots/HASH-2-CRACKED.png` | John the Ripper result showing a recovered PDF password |
| `screenshots/HASH-3-CRACKED.png` | John the Ripper results view with multiple entries and cracking status |

### WK3 PM2 – Hash Calculator and Password Cracker

- Used the NetworkWalks Hash Calculator to load the password-protected PDF and extract a PDF hash in a format compatible with password-auditing tools.
- Used the NetworkWalks Password Cracker demonstration to test candidate passwords.
- Observed the successful match and the completion status.
- Recorded the completion/flag evidence shown by the lab.

**Evidence screenshots**

| Screenshot | What it shows |
|---|---|
| `screenshots/hash calculator 1.png` | Hash Calculator interface with the extracted PDF hash |
| `screenshots/password- cracker.png` | Password Cracker interface showing the successful password match |
| `screenshots/1st Hash Cracked.jpg` | First completion/flag evidence |
| `screenshots/2st Hash Cracked.jpg` | Second completion/flag evidence |
| `screenshots/3st Hash Cracked.jpg` | Third completion/flag evidence |

## Repository Structure

```text
WK3-PM1-PM2-Password-Cracking/
├── README.md
└── screenshots/
    ├── 1st Hash Cracked.jpg
    ├── 2st Hash Cracked.jpg
    ├── 3st Hash Cracked.jpg
    ├── hash calculator 1.png
    ├── HASH-1-CRACKED.png
    ├── HASH-2-CRACKED.png
    ├── HASH-3-CRACKED.png
    └── password- cracker.png
```

## Learning Outcomes

- Understood the role of password hashes in password-protected files.
- Practiced extracting a PDF hash for offline password auditing.
- Observed dictionary-based password testing and result verification.
- Used John the Ripper and web-based lab utilities to compare password-auditing workflows.
- Documented the practical process with screenshots.

## Notes

- All screenshots are stored in the `screenshots/` folder.
- The screenshot names above match the names supplied for this practical.
- No PowerPoint or presentation file is included in this repository.

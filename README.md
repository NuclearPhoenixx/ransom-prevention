# ransom-prevention
![issues](https://img.shields.io/github/issues/Phoenix1747/ransom-prevention.svg?style=for-the-badge) ![open pr](https://img.shields.io/github/issues-pr-raw/phoenix1747/ransom-prevention.svg?style=for-the-badge) ![GitHub last commit](https://img.shields.io/github/last-commit/phoenix1747/ransom-prevention.svg?style=for-the-badge)

This little script will create the files needed in order to prevent an infection with Bad Rabbit and Petya/NotPetya.
In addition to the original Gist this script will work fine on PCs where Windows is not installed on the C: drive and on any non-English computer.

---

Thanks to Rahul Thakare @bantya for his simple yet neat little script, at https://gist.github.com/bantya/f1796317490cbc8d1264565245488e97.

A detailed video about how these files prevent an infection with Bad Rabbit: https://www.youtube.com/watch?v=Y6WOpE92vKc

![image](https://phoenix1747.github.io/host/ransom.png)

## What has been changed:
* Use of %windir% instead of fixed path (C:\Windows\).
* Use of SID S-1-5-32-544 instead of just "Administrators" to make it work properly on non-English computers.
* Installer and uninstaller packed into one script.

**Note: This might not work anymore after a possible ransomware update. Also this is not something to save you from an existing infection - prevention only. So please don't entirely rely on this script!**

**Disclaimer: This is NO guarantee to save you from any kind of infection or similar. Thinking about your internet usage habits will be more of an investment than this.**

2018, Phoenix1747.

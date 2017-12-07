# ransom-prevention
![issues](https://img.shields.io/github/issues/Phoenix1747/ransom-prevention.svg?style=flat-square) ![open pr](https://img.shields.io/github/issues-pr-raw/phoenix1747/ransom-prevention.svg?style=flat-square) ![GitHub last commit](https://img.shields.io/github/last-commit/phoenix1747/ransom-prevention.svg?style=flat-square)

This little script will create some files needed in order to prevent an infection with Bad Rabbit and Petya/NotPetya. In addition to the original gist this script will work fine on PCs where Windows is not installed on the C: drive and on any non-English PC.

---

Thanks to Rahul Thakare @bantya for his simple yet neat little script on https://gist.github.com/bantya/f1796317490cbc8d1264565245488e97.

A detailed video about how these files prevent an infection with Bad Rabbit: https://www.youtube.com/watch?v=Y6WOpE92vKc

![image](https://phoenix1747.github.io/host/ransom.png)

## Changes: 
* Use of %windir% instead of fixed drive letter (C:)
* Use of SID S-1-5-32-544 instead of just "Administrators" to make it work on computers with other languages than English
* Added Uninstaller
* Nice installer interface

**Note: This might not work anymore after a possible ransomware update. Also this is not something to save you from an existing infection - prevention only. So please don't entirely rely on this script and of course be vary of everything you download.**

2017, Phoenix1747.

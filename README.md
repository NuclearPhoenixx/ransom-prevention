# ransom-prevention
![latest version](https://img.shields.io/github/release/Phoenix1747/ransom-prevention.svg?style=flat-square) ![issues](https://img.shields.io/github/issues/Phoenix1747/ransom-prevention.svg?style=flat-square) ![open pr](https://img.shields.io/github/issues-pr-raw/phoenix1747/ransom-prevention.svg?style=flat-square) ![GitHub last commit](https://img.shields.io/github/last-commit/phoenix1747/ransom-prevention.svg?style=flat-square)

This will create some files that will prevent an infection with Bad Rabbit and Petya/NotPetya.

Thanks to Rahul Thakare @bantya for his simple yet neat little script on https://gist.github.com/bantya/f1796317490cbc8d1264565245488e97. This was the inspiration for this repository.

A detailed video about how these files prevent an infection: https://www.youtube.com/watch?v=Y6WOpE92vKc

**ATTENTION: This might not work in the future if the ransomware gets updated. Also this is NOT something to save you from an existing infection - prevention only. So please don't entirely rely on this script and of course be vary of everything you download.**

---

![image](https://phoenix1747.github.io/host/ransom.png)

## Changes: 
* Use of %windir% instead of fixed drive letter (C:)
* Use of SID S-1-5-32-544 instead of just "Administrators" to make it work on computers with other languages than English
* Added Uninstaller
* Nice installer interface

2017, Phoenix1747

# py2to3

> led | 10th March, 2021

___

The purpose of this repo is to convert python2 exploits and scripts to python as the support for python2 has dropped.

## Table of contents
- [CVE-2020-25213](###CVE-2020-25213)
- [CVE-2018-17057](###CVE-2018-17057)

### CVE-2020-25213
The File Manager (wp-file-manager) plugin before 6.9 for WordPress allows remote attackers to upload and execute arbitrary PHP code because it renames an unsafe example elFinder connector file to have the .php extension.
Last Tested on TryHackMe Lab [Badbyte](https://tryhackme.com/room/badbyte).
Script for the CVE is [CVE-2020-25213](CVE-2020-25213.py)

### CVE-2018-17057
LimeSurvey < 3.16 use a old version of "TCPDF" library, this version is vulnerable to a Serialization Attack via the "phar://" wrapper.
This Script was copied from exploit-db. Converting script from python2 to python3 was easy only hex bytes were pain. Instead of strings had to use bytes arrays in ptyhon3.
Last Tested on TryHackMe Lab [Ghizer](https://tryhackme.com/room/ghizerctf).
Script for the CVE is [CVE-2018-17057](CVE-2018-17057)
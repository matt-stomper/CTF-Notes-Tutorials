# CTF Notes, Tools and Tutorials

[TOC]

## Scope

This repo aims to consolidate experience gain from a recent CTF competition recording the different tool, tutorials and notes used during the lead up to and the competition.

Challenges were categorised as the following:

- Investigation
  - Reverse engineering or code and ELF
  - Steganography
  - Cryptography
- Penetration
  - Gain access to a server or webpage 
- Intelligence
  - Searching open source internet
- Detection
  - Analysing network traffic for insider threat and external threat actors

The CTF categorised the difficulty of challenges as follows:

- Novice
- Advanced Beginner
- Competent
- Proficient
- Expert

# Tools

The primary OS used was Kali Linux. https://www.kali.org/ Kali has most of the tools required. Kali can run in VMWare. Running virtual machines is recommended as sometimes the puzzels contain executables where their origin is unknown.

When start a challenge as a beginner, it would be best to look at a reference like Mitre Att&ck - https://attack.mitre.org/techniques/T1187/ to assist with the start point.

## General Tools

1. Cyber Chef - https://gchq.github.io/CyberChef/
2. Crack Station - https://crackstation.net/
3. dCode - https://www.dcode.fr/en
4. Hashes - https://hashes.com/en/decrypt/hash

## Investigation Tools

### Steganography

1. https://stylesuxx.github.io/steganography/

### Cryptography

1. https://cryptii.com/

2. https://towardsdatascience.com/breaking-the-enigma-code-in-python-with-mcmc-marvel-themed-9ceb358dd8ae

### Password cracking

1. https://hashcat.net/wiki/doku.php?id=hashcat
2. https://www.openwall.com/john/
3. Rockyou.txt - https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt
4. https://github.com/henriksb/ZipCrack

### Reverse engineering

1. Ghidra https://ghidra-sre.org/
2. Visual studio Code
   1. Python Extensions
   2. SQL extensions
   3. C extensions

## Network detection tools

1. https://www.wireshark.org/

## Penetration tools

1. Visual Studio Code
   1. Visual Studio with SQL is needed to assist with correct formatting for SQL Injection attacks.
2. NetCat

3. SQL Injection - See the [SQL Injection topic](./topics/SQL_Injection_Readme.md)
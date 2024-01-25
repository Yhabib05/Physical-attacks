# Physical-attacks

In this repository, you will find a series of physical security labs that consist of executing various attacks on cryptographic systems. These labs are designed to provide hands-on experience with different aspects of hardware security, including side-channel analysis, power analysis, and advanced attack methodologies. Utilizing specialized tools like a target: **ARM core embedded in a STM32 micro-controller**, and the ChipWhisperer platform, these labs offer practical insights into the vulnerabilities of cryptographic algorithms and embedded devices. From analyzing power consumption patterns to exploiting hardware faults, these exercises delve deep into the techniques used to breach modern cryptographic systems.

## 1- Intro_SPA.ipynb

This lab introduces passive attacks on embedded devices. It covers tools overview, software and hardware tools used in labs, and demonstrates a Simple Power Analysis (SPA) attack against a simple verify PIN system for access control.

## 2- Leakage_assessment.ipynb

This notebook focuses on leakage assessment, evaluating information leakage through side channels when executing cryptographic algorithms on hardware targets. It explains how significant leakage can compromise the security of cryptographic algorithms.

## 3- DPA.ipynb

The notebook delves into Differential Power Analysis (DPA). It differs from leakage assessment by working to retrieve an unknown key used in AES encryption, using randomly chosen plaintexts and recording power consumption. It includes collecting traces, implementing DPA, key retrieval, and provides further insight into this type of attacks.

## 4- CPA.ipynb

This file discusses Correlation Power Analysis (CPA), a more powerful attack technique that allows quicker key retrieval, using fewer traces than DPA. It involves using datasets from the DPA lab session to demonstrate the efficiency and speed of CPA.

## 5- VerifyPIN_clock_glitch.ipynb

The notebook is based on NewAE Technology tutorials for the ChipWhisperer platform, focusing on Clock Glitching techniques, particularly how they can be used to bypass password protections.

## 6- Fault_Attack_RSA.ipynb

This notebook explores Fault Attacks on RSA encryption, drawing from a 1997 paper by Boneh, Demillo, and Lipton. It also references a blog post by David Wong, providing a practical approach to understanding and executing fault attacks on RSA signatures.

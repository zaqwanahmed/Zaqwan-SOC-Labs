# Lab — Offensive Security Intro (TryHackMe)
**Date:** 05/10/2025  
**Platform:** TryHackMe — Offensive Security Intro

## Objective
Get a hands-on introduction to web attack surface discovery and safe exploit practice using a VM. Understand basic offensive techniques so I can better defend systems as a SOC analyst.

## Steps taken
1. Launched the TryHackMe VM and followed the split-screen tasks.
2. Performed a basic brute-force reconnaissance dirb command in the VM on Terminal on an example bank to exploit sensitive functionality (examples below).
3. Answered lab questions and validated findings in the TryHackMe UI.

## Commands / Evidence
- Example command run: dirb http://fakebank.thm  → output: 'http://fakebank.thm/bank-deposit'
<img width="1709" height="953" alt="Screenshot 2025-10-05 at 02 50 14" src="https://github.com/user-attachments/assets/1ebea345-7f62-477d-9cdf-b322b97f53f8" />

## Screenshots
Bank Deposit from http://fakebank.thm/bank-deposit
<img width="1708" height="953" alt="Screenshot 2025-10-05 at 02 53 50" src="https://github.com/user-attachments/assets/fd8e6aa2-ec8b-495c-9aee-5720e6474fba" />

Successful Hack: 
<img width="1710" height="953" alt="Screenshot 2025-10-05 at 02 54 37" src="https://github.com/user-attachments/assets/253567c9-dce6-4097-ba79-01c2fa25c86a" />

## Lab Completed
<img width="1710" height="947" alt="Screenshot 2025-10-05 at 02 54 58" src="https://github.com/user-attachments/assets/3936a7a5-e438-4cac-a5c7-ca5e889a7262" />

## Findings (3 bullets)
- Ran basic bruteforce 'dirb' commands to expose sensitive functionality to users via secret URLs. 
- Observed how web input points can be probed safely in a controlled environment.  
- Gained initial understanding of the offensive techniques that SOC teams must detect and mitigate.

## Next steps
- Complete Defensive Security Intro room.  

## Tags
#TryHackMe #Offensive #SOC #Lab

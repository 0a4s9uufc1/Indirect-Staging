### REPO ARCHIVED
Archiving this repo since its a very old project of mine that I broke and never continued.

### Payload Loader Features

- Remote code injection support
- Classic remote process injection via indirect syscalls
- API Hashing
- String Hashing
- No CRT library imports
- Brute Force Decryption
- Self Deletion
- ~~Anti-Analysis features~~

  
---
### Description

This is a project that I have been working on for a couple weeks now. I have been doing malware development for probably 5 months or so now and I am still learning so much and I originally made this just to learn how to use payload staging to have the malware download the shellcode from the internet instead of having the shellcode inside of the binary to avoid static analysis. But then had the thought of just making it a full project.
I would love feedback on the project and how I could improve it!

### Upcoming Features

- Execution Delay
- Anti-Virtualisation

### INFO

I had big help from the MalDev Academy course to be able to make this happen. And there are still so many improvements I can Make into this and features that I want to impliment. I will still be working on this until I feel that It is complete.

### Usage
Inside the main.c file at the top are definitions that have the url for the shellcode that is used for payload staging and the process name that you will inject the shellcode into. Change these as you wish.

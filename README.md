# Password-Cracking-Lab
Password cracking lab using Hexstrike MCP, Claude Desktop, Kali Linux and John the Ripper to recover a protected PDF password.
*Tools Used*

- Hexstrike MCP
- Claude Desktop
- Kali Linux
- John the Ripper
- http://pdf2john.pl
- RockYou Wordlist

*PDF Hash Extraction*

I downloaded the password-protected PDF from the lab. I used http://pdf2john.pl to extract the hash from the PDF. The hash was saved in a file so John the Ripper could use it for cracking.

*Cracking Process*

I used John the Ripper with the RockYou wordlist to crack the hash. John compared each password in the wordlist to the hash until it found the correct password.Add it inside Johnny is the graphical version of John the Ripper, so it does the same cracking but with buttons instead of typing commands.


*Password Found:* `crackthepdf`

I used the password to open the PDF and confirmed it worked.

*What I Learned*

- Weak passwords can be cracked fast with wordlists
- Common passwords like in RockYou are not safe
- Longer passwords with symbols are harder to crack

*How to Protect Passwords Better*

- Use long passwords with letters, numbers and symbols
- Do not use common words
- Use a password manager
  
*Acknowledgement*
I would like to appreciate NETWORKWALKS and my tutor for giving me this opportunity to learn.

  *Conclusion*

This lab showed me how password cracking works and why strong passwords matter.

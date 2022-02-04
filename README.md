# Dransomware

## About:
* Title: Dransomware
* Description: Ransomware which encrypts users data without root privileges
* AUTHOR: drapl0n
* Version: 1.0
* Category: Ransomware
* Target: GNU/Linux
* Attackmodes: HID

## Dransomware is USB Rubber Ducky Script with ransomware which will encrypt user's data without root privileges in 30 sec's.

* Deploy Dransomware, negotiate with victim and acquire ransom in exchange of private key.
* Tested on Kali linux and Parrot OS.
* Only for educational purpose.
### Changes to be made:
* Change Public Key in [importing gpg public key] section.
* Change your key name in [dransomware] section.
* Optional: You can change paths. [Be carefull while doing this].
* Change your contact details in order to contact user and acquire ransom.

### Workflow:
1. Stop storing history, this helps to keep tracks clear from begining.
2. Importing Public GPG key (this can be done by storing key on server and fetching it via wget or curl to reduce execution time).
3. Creating non-root systemd service.
4. Deploying Ransomware.
5. Autostarting service on opening terminal with shell (bash and zsh).
6. Entering Message.

#### Support me if you like my work:
* https://twitter.com/drapl0n

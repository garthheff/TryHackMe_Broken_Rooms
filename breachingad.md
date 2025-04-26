https://tryhackme.com/room/breachingad

# Task 6 Microsoft Deployment Toolkit

Advises 
"Note as well that if the network has just started, these file names will only update after 10 mintes of the network being active."

Issue: Technically correct, but took 20+ minutes not 10.

# Task 7 Configuration Files
Issue, The following does not work in the attack box with python2, needs to be python3
thm@thm:~/root/Rooms/BreachingAD/task7/mcafee-sitelist-pwd-decryption-master$ python2 mcafee_sitelist_pwd_decrypt.py <AUTH PASSWD VALUE>

Fix: thm@thm:~/root/Rooms/BreachingAD/task7/mcafee-sitelist-pwd-decryption-master$ python3 mcafee_sitelist_pwd_decrypt.py <AUTH PASSWD VALUE>


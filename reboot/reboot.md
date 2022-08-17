## Reboot

### Requirements 
1. Target device has to logged in with credentials
2. Flash the code into attiny85 
3. Connect to device and wait
4. it will be loop sometimes it leads grub loader and different boot shell access.
5. System must Linux machine

### Code Explanation
  DigiKeyboard.sendKeyStroke(0); - Taking as enter 
  DigiKeyboard.println("reboot"); - printing as command
  
  So it is easy one but fun one 

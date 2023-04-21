# keycroc_demo
Password harvesting and stealthy inject

## SUMMARY
This project is a quick, standalone demo of using keycroc to capture a password. Once the user is idle, it uses the password to login and inject a payload.

## INSTALLATION
  - Enter arming mode on your keycroc
  - Drop keycroc_demo.txt into the keycroc's **payload folder**
  
## DEMO STEPS
  1. User uses GUI+l to lock the screen
  2. User types password, then ENTER (keycroc captures password starting at GUI+l until ENTER)
  3. User uses GUI+l to lock screen again, triggering phase 2
  4. Keycroc waits 5 secs
  5. Keycroc logs in with captured password
  6. Keycroc injects payload (opens a terminal and types out a skull ASCII art. Can be easily replaced with another payload)
  
## TESTED ON
  - Kali linux (the payload is specific to kali/debian)

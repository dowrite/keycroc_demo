# keycroc_demo
Password harvesting and stealthy inject

## SUMMARY
This project is a quick, standalone demo of using keycroc to capture a password. Once the user is idle, it uses the password to login and inject a payload.

## INSTALLATION
  - Enter arming mode on your keycroc
  - Drop keycroc_demo.txt into the keycroc's **payload folder**
  
## DEMO STEPS
  - User uses GUI+l to lock the screen
  - User enters password (keycroc captures it)
  - User uses GUI+l to lock screen again
  - Keycroc waits 5 secs
  - Keycroc logs in with captured password
  - Keycroc injects payload (opens a terminal and types out a skull ASCII art. Can be easily replaced with another payload)
  
## TESTED ON
  - Kali linux (the payload is specific to kali/debian)

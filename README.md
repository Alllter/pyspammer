# pyspammer
A simple 5 lines of code spammer, Using PyCharm

# Requirement
- PC/VPS
- PyCharm
- Python

# How To Use
- Install PyCharm
- Open spammer.py files
- Open spammertext.txt, And write text that you want to spam
- Click on run button, And run it!

# Codes
```import pyautogui, time
time.sleep(5)
f = open("spammertext", 'r')
for word in f:
    pyautogui.typewrite(word)
    pyautogui.press("enter")
    
    #Made by Alter#1098
    #You can use this on Instagram, Whatsapp and etc!
    #Simple python 5 lines of code spammer.
    #Any problem? dm Alter#1098
    #Make sure you are using PyCharm Edu!

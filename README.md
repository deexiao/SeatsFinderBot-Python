# SeatsFinderBot
An auto class enroll Bot made for ASU Students written in Python 3.

## System Requirements
1. Python 3
2. ChromeDriver installed: http://chromedriver.chromium.org/
## Sample command
python3 SeatsFinderBot.py --choice "swap" --username ".." --password ".." --swapwith 12345 --section 54321 --guid ".."

## Command Arguments

### -c or --choice
SeatsFinderBot supports "swap" or "add" for your wanted course.

### -u or --username
Your myASU username, eg: "qwe123"

### -p or --password
Your myASU password, eg: "QWEqwe123"

### -ss or --semester 
Semester for your class, "Spring+2019" is set to default so you can skip it.

### -sw or --swapwith
Class number you would like to swap with (already enrolled), eg: 12345

### -s or --section
Class number you would like to enroll, eg: 54321

### -r or --reserved
If the class you want to track has reserved seats, specify it here, because my server only checks above 0 situation, eg: 5

### -g or --guid
Key to use this app, eg: "12345-qwert-zxcvb-67890"

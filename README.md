# SeatsFinderBot
An auto class enroll bot made for ASU Students written in Python 3.

SeatsFinderBot is an Open Source project, it does not collect your ASU username and password.

## System Requirements
1. Python 3 
2. ChromeDriver installed: http://chromedriver.chromium.org/
3. ```cd``` to the project, and then ```pip3 install``` all missing packages

## Sample command
* ```python3 SeatsFinderBot.py --choice 'swap' --username 'a' --password 'a' --swapwith 12345 --section 54321```
* ```python3 SeatsFinderBot.py --choice 'add' --username 'a' --password 'a' --section 54321 --timeinterval```

#### Default arguments
* ```--reserved``` is set to ```0```
* ```--semester``` is set to ```'Spring+2019'```
* ```--timeinterval``` is set to ```10``` seconds

## Command Arguments

#### ```-c``` or ```--choice```
SeatsFinderBot supports 'swap' or 'add' for your wanted course.

#### ```-u``` or ```--username```
Your myASU username, eg: 'qwe123'

#### ```-p``` or ```--password```
Your myASU password, eg: 'QWEqwe123'

#### ```-ss``` or ```--semester```
Semester for your class, 'Spring+2019' is set to default so you can skip it.

#### ```-sw``` or ```--swapwith```
Class number you would like to swap with (already enrolled), eg: 12345

#### ```-s``` or ```--section```
Class number you would like to enroll, eg: 54321

#### ```-r``` or ```--reserved```
If the class you want to track has reserved seats, specify it here, because my server only checks above 0 situation, eg: 5

#### ```-t``` or ```--timeinterval```
Time interval is 10 seconds by default, it means the program will check every 10 seconds

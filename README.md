# SeatsFinderBot
An auto class enroll bot made for ASU Students written in Python 3.

SeatsFinderBot is an Open Source project, it does not collect your ASU username and password.

**SeatsFinderBot now has Web App designed by Zhen Qian: [Link](http://72.201.206.220:8000/)**

## System Requirements
1. Python 3 
2. ChromeDriver installed: http://chromedriver.chromium.org/
3. ```cd``` to the project, and then ```pip``` all missing packages like follows:

#### Mac / Linux
* ```pip3 install selenium```
* ```pip3 install webdriver_manager```

#### Windows
* ```py -m pip install selenium```
* ```py -m pip install webdriver_manager```

## Sample command

#### Mac / Linux
* ```python3 Bot.py -l 'GRAD' -c 'swap' -u 'abc' -p 'abc' -sw 12345 -s 54321 -t 30```
* ```python3 Bot.py -l 'UGRD' -c 'add' -u 'abc' -p 'abc' -s 54321 -t 20```

#### Windows
* ```py Bot.py -l GRAD -c swap -u abc -p abc -sw 12345 -s 54321 -t 30```
* ```py Bot.py -l UGRD -c add -u abc -p abc -s 54321 -t 20```

#### Default arguments
* ```--reserved``` is set to ```0```
* ```--semester``` is set to ```'Spring+2019'```
* ```--timeinterval``` is set to ```10``` seconds

## Command Arguments

#### ```-l``` or ```--level```
SeatsFinderBot supports 'UGRD' (undergraduate) or 'GRAD' (graduate) for your level of study.

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

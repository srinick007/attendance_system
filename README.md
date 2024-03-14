# Face Recognition Attandance System

### Recognize The faces And Take Automatic Attandance. :sparkles:

## Installation

### create enviroment (highly suggested)

recommended python version == 3.7

First open the terminal or command line in the IDE.Then write the following code.
```
python -m venv env
```
Then activate the enviroment using the code below for windows.
```
.\env\Scripts\activate
```
[ *Notice:*
If your pc don't have virtual enviroment or pip install the follow this link.
[How to create Virtual Enviroment](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) ]

git clone the repo

```bash
git clone https://github.com/srinick007/attendance_system.git
```

change directory to FRAS

```bash
cd FRAS
```

install requirements
```bash
pip install -r requirements.txt
```

create two folders inside FRAS with the following names:

```bash
TrainingImage
ImagesUnknown
Attendance
```


## running

change directory to FRAS
```bash
cd FRAS
```
run main.py

```bash
python main.py
```

![image](https://github.com/srinick007/attendance_system/assets/97779349/e9a2c05a-5a53-4259-92ef-c823fd8b8b98)

1 - check camera is functional

2 - capture training images of person for attendance. enter unique name(without spaces and special characters) and unique id.
    camera open and wait for 20 seconds for each person.for each person 101 images are captured and stores in TrainingImages folder. after capturing open TrainingImages and no images other then faces are there . if random image is present delete it.

3 - train the model after capturing images of person

4 - run attentance system. the attendace list will be saved in attendance folder. click on camera and press q to stop taking attendance

6 - quit the program


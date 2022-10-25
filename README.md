# Linux MCQ Test on CMD Terminal from Bash Script
[![made-with-Bash](https://img.shields.io/badge/Made%20with-Bash-1f425f.svg)](https://www.gnu.org/software/bash/)
![image](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


Hello Friends,
Recently I wanted to test my skill-set in Linux for review. I searched online for a free MCQ-like exam for LInux but unfortunately couldn't find one. So I decided to create one MCQ test exam script entirely written in Bash Shell script. After many hours of work here I am presenting a Linux MCQ test of 1000 questions in bash. 

### Linux MCQ Test Image

![Question1](https://github.com/santosh2712/linux_mcq_test_1000_question_in_bash_shell_script/blob/main/.linux_mcq_images/question1.png?raw=true "Question1")

## Why is it written in Bash? 
Because it is easy and super portable. Most Linux boxes are running with bash. And as a Linux admin, it is easy to do so. Bash shell is the native way of interacting with Linux. In terms of portability just copy the folder on any linux box running with bash and required dependency and it would work. 

## Does it require an Internet connection? 
No, it doesn't require any working internet connection for the MCQ Test Exam. 

## Does it save any personal data? 
It's a completely offline application and doesn't save any user data online.  All data is saved locally in the user system.

## Application requirements / Dependency. 
The application requires the following commands installed on your system. Some of them are built-in commands with bash but ensure those commands are present or already installed on your system before starting the MCQ test exam. 
### Requried Package Names
- bash
- sudo
- gpg
- awk
- sed
- read
- mkdir
- date
- basename
- readlink
- realpath

## NOTE: Use in black Background in Terminal for better usability. 

### Recommendation 
Install shc package

##### RHEL Family Distros
#enable epel repo 
```
yum install epel-release
yum --disablerepo=* --enablerepo=epel install shc -y 
```    

##### Ubuntu 

```    
sudo apt install shc 
```

## How to use this application? 
The steps to use this application are as follows 
##### Note: Ensure git is already installed on your system.

Clone the repo with the following command.
```
git clone https://github.com/santosh2712/linux_mcq_test_1000_question_in_bash_shell_script.git
```

once the repository is copied on your system. Change directory to repository directory with cd command. 
```
cd linux_mcq_test_1000_question_in_bash_shell_script/
```
Just start the MCQ test by running the following command on the terminal.
```
[santosh@CentOS8 linux_mcq_test_1000_question_in_bash_shell_script]$ ll
total 60
-rwxrwxr-x. 1 santosh santosh 57240 Sep 28 14:19 linux_mcq_test_1000_question_in_bash_shell_script_by_santosh_kulkarni
-rw-rw-r--. 1 santosh santosh   102 Sep 28 14:19 README.md
drwxrwxr-x. 2 santosh santosh     6 Sep 28 14:19 Temp
[santosh@CentOS8 linux_mcq_test_1000_question_in_bash_shell_script]$ ./linux_mcq_test_1000_question_in_bash_shell_script_by_santosh_kulkarni
```
#### Note: Do not use sh or bash command to start. its LSB executable file. As shown in below 
```
# file linux_mcq_test_1000_question_in_bash_shell_script_by_santosh_kulkarni
linux_mcq_test_1000_question_in_bash_shell_script_by_santosh_kulkarni: ELF 64-bit LSB executable, x86-64, version 1 (SYSV), dynamically linked, interpreter /lib64/ld-linux-x86-64.so.2, for GNU/Linux 2.6.32, BuildID[sha1]=45be113f836f866ede9239399db1ad7de6ccc747, stripped
```

On checking of dependency, requirement user will be asked for the username as shown below enter username without spaces 
##### Starting the Linux MCQ test 

```
./linux_mcq_test_1000_question_in_bash_shell_script_by_santosh_kulkarni
```
As shown in image below 


![Starting Linux MCQ Test](https://github.com/santosh2712/linux_mcq_test_1000_question_in_bash_shell_script/blob/main/.linux_mcq_images/Starting_script.png?raw=true "Starting Linux MCQ Test")

It will start or resume an MCQ test session for the user. On fresh start choose the number of MCQ test chapters you want to take test. As shown in below image.


![Choose MCQ test Chapter](https://github.com/santosh2712/linux_mcq_test_1000_question_in_bash_shell_script/blob/main/.linux_mcq_images/choose_exam_chapter.png?raw=true "Choose MCQ test Chapter")

This will start MCQ Test EXAM for user. As shown in below image.

![Question1](https://github.com/santosh2712/linux_mcq_test_1000_question_in_bash_shell_script/blob/main/.linux_mcq_images/question1.png?raw=true "Question1")

#### Note: You have to input only Option A or B or C or D to choose your answer. As shown in above pic. If The answer is correct following window will be shown.

![Question1_ans](https://github.com/santosh2712/linux_mcq_test_1000_question_in_bash_shell_script/blob/main/.linux_mcq_images/question1_ans.png?raw=true "Question1_ans")

#### It will wait for 10 Seconds to see the expanation of the answer. Later it will move to next Question in chapter. As shown in below image.

![Question2](https://github.com/santosh2712/linux_mcq_test_1000_question_in_bash_shell_script/blob/main/.linux_mcq_images/question2_window.png?raw=true "Question2")

##### It will Update Question Completed , Correct Answer and Incorrect Answer Column . As shown in above image.

# Features: 
This application has following features.

### Written in Bash Shell
It is written entirely in bash. No major dependency overhead as bash is part of major Linux distributions.  

### Portable 
Since it's a shell script. We can port this application to any linux box by copying the script directory. Ensure dependency packages are installed on the system.

### Offline in use
It's a complete offline application.

### Result Status Bar
The live MCQ test status bar will be shown in the application terminal. With this users can keep an eye on overall progress and performance on the test, like Total Questions, Correct answers, and Incorrect answers. 

### Resume Functionality
This is one of the best features of the script. It has a question set of 1000  questions. Attempting to complete a chapter in one go is quite difficult for anyone. Hence resuming the MCQ test is quite a good feature, It saves user time and energy.

### Light in resource usage.
Super lite in nature as it only uses a few command. It can be run on any linux box.

### Check The Repository and download recent version of the application
### Repository Link: 
```
https://github.com/santosh2712/linux_mcq_test_1000_question_in_bash_shell_script
```

## Please consider giving a  STAR to the repo. It will help in keeping  the repo and app alive.

LCPT (Linux Command Practice Test)

Welcome to the Linux Command Practice Test repository! This repository contains a script named SYSTEM_INFORMATION designed to help users practice and learn essential Linux system information commands in an interactive and engaging way.
Description

![image](https://github.com/Ronald0Code/LCPT/assets/59511049/8d566390-b13c-4e60-bbaf-11c508a1210a)


The SYSTEM_INFORMATION script is a Bash script that quizzes users on various Linux system information commands. The script uses fun tools like cowsay and figlet to enhance the user experience, making the learning process enjoyable. This practice test is ideal for those looking to reinforce their knowledge of Linux commands, whether they are beginners or experienced users brushing up on their skills.
Features

    Interactive Quiz: Users are prompted with questions and must type the correct Linux command as an answer.
    Immediate Feedback: After each question, the script provides feedback on whether the user's answer was correct or not, along with the correct command if the user was wrong.
    Visual Enhancements: Utilizes cowsay and figlet to make the learning experience more enjoyable.
    Comprehensive Coverage: Includes a wide range of commands related to system information, making it a thorough practice tool.

Installation

Before running the script, ensure that you have cowsay and figlet installed on your system. The script will attempt to install these tools if they are not already available.
Install Required Packages

bash

sudo apt-get install cowsay figlet

Usage

Clone the repository and navigate to the directory:

bash

git clone https://github.com/Ronald0Code/LCPT.git
cd LCPT

Make the script executable and run it:

bash

chmod +x SYSTEM_INFORMATION
./SYSTEM_INFORMATION

Script Overview

The script presents a series of questions related to Linux system information commands. Here are some examples of the questions included:

    Display Linux system information: uname -a
    Display kernel release information: uname -r
    Show which version of Red Hat is installed: cat /etc/redhat-release
    Show which version of Ubuntu is installed: lsb_release -a
    Show how long the system has been running and load averages: uptime
    Show system host name: hostname
    Display all local IP addresses of the host: hostname -I
    Show system reboot history: last reboot
    Show the current date and time: date
    Show this month's calendar: cal
    Display who is online: w
    Show who you are logged in as: whoami

Contribution

Contributions are welcome! If you have any suggestions for new questions or improvements to the script, feel free to open an issue or submit a pull request.









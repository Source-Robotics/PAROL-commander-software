# How to install Windows
    Install python 3: https://www.python.org/downloads/
    Installing Python should also install pip3
    Install git: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
    
    pip3 install git+https://github.com/PCrnjak/s_visual_kinematics.git@main#egg=s_visual_kinematics
    pip3 install customtkinter
    pip3 install customtkinter --upgrade
    pip3 install oclock
    pip3 install pyserial
    
     pip3 install roboticstoolbox-python==1.0.3
    
    pip3 install swift-sim==1.0.1
    pip3 install pgraph-python
    pip3 install progress
    pip3 install numpy==1.23.4
    pip3 install scipy==1.11.4
  
## Clone commander repo
    git clone https://github.com/Source-Robotics/PAROL-commander-software.git

## To run, go to the GUI/files folder of the clone and start the commander
    cd PAROL-commander-software/GUI/files
    python3 Serial_sender_good_latest.py

## If using Visual Studio code
    install python extension
    Run in the VS code

## If connecting over GUI enter (x is your port number):
    COMx 
Press connect multiple times

## Troubleshooting
Check In https://github.com/Source-Robotics/PAROL-commander-software/tree/main/Working%20dependency what python module versions were used on working systems

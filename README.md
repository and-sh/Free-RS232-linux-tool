# Free-RS232-linux-tool
This is the copy of
https://github.com/damogranlabs/serial-tool
But I rewrite a little a code. Now you do not need to install anything (just dependencies, like aioserial, if they are not already in your system. Python will tell you that he need). This is usefull if you not interested in Python itself and just need a tool. pip and insolated enviroment represents itself as some hedache.

Just download the code and run app.py

python3 app.py

or run app.py from IDLE

The code contains error - it can not correctly determine the name of usb adapter.
You should write correct name here.
![Screenshot From 2025-06-29 09-24-59](https://github.com/user-attachments/assets/532fe5d7-c95d-4855-8484-febbadd4ada5)

you can check correct name by command

ls -l /dev/ttyUSB* /dev/ttyACM*

If you find this complicated try to use CuteCom. It already added to some distributives.

    Debian and Ubuntu: sudo apt install cutecom
    Fedora: sudo dnf install cutecom
    openSUSE: sudo zypper install cutecom

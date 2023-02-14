# Night-Light
Toggle blue light for Ubuntu Unity Environment

1. Open a terminal on Ubuntu.
2. Install Python3 if not already installed. You can do this by running the following command:
sudo apt-get update
sudo apt-get install python3

3. Install tkinter library which is used for the GUI by running the following command:
sudo apt-get install python3-tk

4. Copy the code and save it to a file named "night_light.py" on your system.
5. Open a terminal and navigate to the directory where you saved the "night_light.py" file.
6. Run the following command to make the script executable:
chmod +x night_light.py

7. Now you can run the night_light.py script by executing the following command in the terminal:
./night_light.py

8. The GUI will appear and you can enable or disable the night light by clicking on the "Night Light" checkbox.


To make the night_light.py script start upon startup of the OS, you can add it as a startup application in Ubuntu. Here are the steps to do so:

1. Open the "Startup Applications" application. You can search for it in the Activities menu or in the Ubuntu Software Center.
2. Click the "Add" button to add a new startup application.
3. In the "Name" field, enter "Night Light" or any name of your choice.
4. In the "Command" field, enter the full path to the night_light.py script. For example, if the script is located in your home directory, the command should be /home/your_username/night_light.py. Make sure to replace "your_username" with your actual username.
5. In the "Comment" field, you can optionally enter a brief description of what the script does.
6. Click "Add" to save the startup application.
7. Restart your computer and the night_light.py script should start automatically on startup. If it does not start automatically, you can also manually start it from the terminal using the ./night_light.py command.

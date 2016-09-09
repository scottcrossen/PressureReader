██████╗ ██████╗ ███████╗███████╗███████╗██╗   ██╗██████╗ ███████╗
██╔══██╗██╔══██╗██╔════╝██╔════╝██╔════╝██║   ██║██╔══██╗██╔════╝
██████╔╝██████╔╝█████╗  ███████╗███████╗██║   ██║██████╔╝█████╗  
██╔═══╝ ██╔══██╗██╔══╝  ╚════██║╚════██║██║   ██║██╔══██╗██╔══╝  
██║     ██║  ██║███████╗███████║███████║╚██████╔╝██║  ██║███████╗
╚═╝     ╚═╝  ╚═╝╚══════╝╚══════╝╚══════╝ ╚═════╝ ╚═╝  ╚═╝╚══════╝
██████╗ ███████╗ █████╗ ██████╗ ███████╗██████╗ 
██╔══██╗██╔════╝██╔══██╗██╔══██╗██╔════╝██╔══██╗
██████╔╝█████╗  ███████║██║  ██║█████╗  ██████╔╝
██╔══██╗██╔══╝  ██╔══██║██║  ██║██╔══╝  ██╔══██╗
██║  ██║███████╗██║  ██║██████╔╝███████╗██║  ██║
╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═════╝ ╚══════╝╚═╝  ╚═╝

BYU PHSCS 245 Project
OWNER: Scott Leland Crossen
CONTRIBUTERS: Scott Crossen
	      Ryan Doel (Team Captain)
	      Kamdon (Riding on the coatails of the team)

SUMMARY:
This is a project designed to quickly gather pressure information from baratrons. It can also be used to gather most voltage measurements across the first two channels of a DAQ.

INSTRUCTIONS:
- Plug in your 1000 Torr Baratron to DAQ Analog Input 0.
- Plug in your 10 Torr Baratron to DAQ Analog Input 1.
- Create a .txt or other tab-delim file with a regular file browser.
- Point the program to that file. It will Erase and re-record over whatever you have in the file each time.
- Run the program. It immediately starts taking data and recording it as voltage measurements with format [time stamp][1000 Torr Baratron Voltage][10 Torr Baratron Voltage].
- You'll have to analyze the data on a separate program and adjust it with calibration constants for your given baratrons.

CONTACT:
Scott Leland Crossen	scottcrossen42@gmail.com	scottcrossen42.com

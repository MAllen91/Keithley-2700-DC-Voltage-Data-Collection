This is a python script meant to connect to a Keithley 2700 multimeter/data logger. 
Please note that there are 2 places in the program where the CSV must be changed each time the program is closed and restarted. 
Program will not write to CSV is the CSV is open during the scanning and writing events. For this reason a timer is included and displayed for the user. Timer is in seconds, by default the program will scan every 10 minutes.

Adapted from code written by jesseadamczyk. https://github.com/jesseadamczyk/keithley2700-tutorial

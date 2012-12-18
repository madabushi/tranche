#This is a basic shell script to display the following options in a Menu:
#1. Change Password
#2. Diskspace Status
#3. Logon to ssh
#4. Services Status
#5. Open Ports
#6. Java Apps Running
#7. Kill PID
#8. Kill Process/App by name
#9. Quit

# Run the script as ./menu

Additional Comments:
This is a quick way to define the menu. The code could be trimmed further, but added some lines as a cross check - echoing ps status, etc.
In case we want to add more options, all we need to do is to add to the below 'Menu' which stores all the menu options, and make corresponding changes by appending code. Hope this helps. 

Used clear initially so that the menu is displayed on a clear screen.
Normally passwd -stdin $name would also work. But I think Ubuntu requires it this way.
Gave '|less' so that the screen looks clean, and the port count is clearly known.
I had the kill function to be able to kill both PID wise as well as process name wise.
The ps status might prolong the code and could be avoided, but I added just as a cross-check.
   

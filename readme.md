# WILLIAM - Just A Rather Very Intelligent System
<br>

##### This project currently uses Python version 2.7 or 3.6

This project can be an audio assistant on your operating system and perform the tasks that you are considering for it.
You can use different scripts to use in the language interface

Part of the conversations you can do with WILLIAM:
- ### Converses, barely.

    **Talk to WILLIAM :** hello<br>
    **WILLIAM :** Well, hello

    **Talk to WILLIAM :** baby?<br>
    **WILLIAM :** Sir.


WILLIAM is not able to learn, and you can increase the sentences with WILLIAM (remember WILLIAM)
To do this, you can open the file and add your own conversations and send us

- ### Rhythmbox: Play, Stop, Open.

    Uses shell commands to play and pause rhythmbox music.

    **Talk to WILLIAM :** play music<br>
    **WILLIAM :** On it!<br>
    **Talk to WILLIAM :** Stop music<br>
    **WILLIAM :** On it!<br>
    **Talk to WILLIAM :** Next Track<br>
    **WILLIAM :** Right away, sir!
    **Talk to WILLIAM :** Previous Track<br>
    **WILLIAM :** Right away, sir!

- ### Tells time.
    
    **Talk to WILLIAM :** what time is it?<br>
    **WILLIAM :** The time is 4 43 am


- ### Suggests Googling for all unrecognized interrogative questions

    **Talk to WILLIAM :** What is IIT, Bombay?<br>
    **WILLIAM :** Do you want me to google that for you?<br>
    **Talk to WILLIAM :** yes<br>
    **WILLIAM :** Right away, sir!  Created new window in existing browser session.


    Uses youtube.py script to find the first search result for the last user input in above case, and opens it in chromium browser. (Thanks for the nihal111)

- ### Searches internet.

    **Talk to WILLIAM :** Google what is the answer to life?<br>
    **WILLIAM :** Right away, sir!  Created new window in existing browser session.<br>
    **Talk to WILLIAM :** Search youtube for Call of Duty<br>
    **WILLIAM :** On it!  Created new window in existing browser session.<br>
    **Talk to WILLIAM :** Search for Reza Aghajani on google maps<br>
    **WILLIAM :** On it!  Created new window in existing browser session.

- ### Changes Wallpaper.

    In the WILLIAM folder, a folder is placed for the wallpapers so you can put your own images in the appropriate path and change the image to change the wallpaper.

    **Talk to WILLIAM :** change wallpaper<br>
    **WILLIAM :** On it!
- ### Volume Controls.
    **Talk to WILLIAM :** increase valume to *<br>
    **WILLIAM :** Right away, sir!<br>
    **Talk to WILLIAM :** decrease valume to *<br>
    **WILLIAM :** Right away, sir!<br>
- ### Launches Programs.
    
    **Talk to WILLIAM :** open nautilus<br>
    **WILLIAM :** Right away, sir!<br>
    **Talk to WILLIAM :** take me to /etc<br>
    **WILLIAM :** Sure thing! (Opens /etc in nautilus)<br>
    **Talk to WILLIAM :** take me home<br>
    **WILLIAM:** Sure thing! (Opens ~ in nautilus)<br>
    **Talk to WILLIAM:** open chromium / open firefox / open calculator / open vlc<br>
    **WILLIAM :** Sure thing!


- ### Other:
    
    Standard replies for unrecognized/unmatched inputs

    **Talk to WILLIAM :** go to sleep / exit / quit / bye / goodbye

    closes the python script.

## Requirements:

You can run `pip install -r requirements.txt` to install them all.

for Graphic install PyQT4:

`sudo apt install python-qt4`
`sudo pacman -S python2-pyqt4`
`sudo pacman -S python-pyqt4`

## Run:

To run, you can enter the WILLIAM path and execute the following commands in voice mode


`python script.py` : for Graphic mode and voice mode of input

Voice mode may give a series of warnings for numerous reasons, but still might fuction properly.

## Exit:

To exit and close the program, you must first close the graphic window and then stop the terminal output with Ctrl + Z control keys.

And finally I thank Nihal Singh for the original code


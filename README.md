# EggBot
an egg painting robot inspired by many other Eggbots out there.

the Eggbot is build on an wooden base with NEMA17 motors and motor mounts, a small servo for pen actuation and 3D printed parts. it is controlled using grbl (https://github.com/grbl/grbl ;compiling works only with old arduino versions ! https://www.arduino.cc/en/Main/OldSoftwareReleases#previous), while the gcode is send over serial with baud rate 115200 using "Universal Gcode Sender" (https://winder.github.io/ugs_website/) or "Printrun" (https://www.pronterface.com/) or similiar programs. The gcode was generated in inkscape (https://inkscape.org/) using the unicorn plugin (https://github.com/martymcguire/inkscape-unicorn ;works only in old inkscape verion). In theory any other program can be used to generate the gcode.

this repository includes all 3D files for mechanical parts and gcode for the easter bunny drawing as seen in the following video \
[<img src="https://img.youtube.com/vi/t_Bkus4Qe7w/maxresdefault.jpg" width="20%">](https://youtu.be/t_Bkus4Qe7w)

i had only one issue with this build. When the pen is raised up the sevo can pull it so rapid that it filps over and is stuck that way. to avoid that you should limit the travel of the pen hinge.

here are some images:<br>
<img src="/eggbot.JPG" style="width:20%;">
<img src="/eggbot.PNG" style="width:20%;">

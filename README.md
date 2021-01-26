# sei_automatic_courses_player
[SEI] This module should help you to quickly connect to your online video course for semester 2

Startmyclasses has the following dependencies:
dpkg, xclip, khal(optional)

>### To install startmyclass, do as follows :
>
>-Go to the startmyclass directory and open terminal
>-Run the command 'sudo ./INSTALL'
>-Follow the instruction if it is displayed that other packages are necessary
>-You can now run startmyclass by typing "startmyclass"

-If you wish to use the calendar (with khal installed) option, you should update the calendar at least once ("startmyclass -u"). This operation should be done at least weekly for correct results.


### To modify the zoom links or classes, do as follows:
You may simply open the "launcher" file in **usr/lib/.startmyclass/launcher**. Keep in mind that all of your changes wil be overwritten when the package is updated. If you want to keep your changes, consider a merge request.

NB:
If you already use khal as agenda, it could interfere with this program, so be sure to save all your personal agendas, and your config files before using any command wich works with khal.

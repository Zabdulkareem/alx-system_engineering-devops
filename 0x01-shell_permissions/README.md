##This file contains a description for each of the scripts used in this project

- 0. ***su betty*** switches the current user to betty.
- 1. ***whoami*** script will print the effective username of the current user.
- 2. ***groups*** command will print all the groups the current user is part of.
- 3. ***chown*** betty hello* changes the owner of the hello file to the user betty.
- 4. ***touch hello*** will create an empty 'file'.
- 5. *chmod u+x hello* command will add execute permission to the owner of the file 'hello'.
- 6. *chmod ug+x, o=r hello* command will grant the owner and group execution right only while granting the others read only permission for the file 'hello'.
- 7. *chmod a+x* command grants the owner, groups and others execution right.
- 8. *chmod 007 hello* excludes all the users except the others from read, write, execute permissions.
- 9. *chmod 753 hello* sets the mode of the file hello to __rwxr-x-wx__
- 10. *chmod --reference=hello olleh* sets the mode of olleh as that of hello
- 11. *find *
- 12. **mkdir -m 751 my_dir** creates a directory (my_dir) with 751 permissions.
- 13. *chgrp school hello* changes the group owner to school for the file 'hello'.
- 14. *chown vincent:staff* command changes the owner to vincent and group owner to staff for all the files in the working directory.
- 15. *chown -h vincent:staff _hello* command will change the owner and group owner of _hello to vincent and staff from the working directory.
- 16. *chown --from=guillame betty hello* command will change the owner of the hello file to betty only if it is owned by the user guillaume
- 17. *telnet towel.blinkenlights.nl* command will play the StarWars fourth episode in the terminal.

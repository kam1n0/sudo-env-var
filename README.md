# sudo-env-var
*Credit goes to Tib3rius* | https://tryhackme.com/room/linuxprivesc

Sudo can be configured to inherit certain environment variables from the user's environment.

Run 'sudo -l' and check which environment variables are inherited (look for the 'env_keep' options):

LD_PRELOAD and LD_LIBRARY_PATH are both inherited from the user's environment.
* LD_PRELOAD loads a shared object before any others when a program is run.
* LD_LIBRARY_PATH provides a list of directories where shared libraries are searched for first.



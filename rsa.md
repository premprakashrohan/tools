####create and add ssh key in Windows :-####
open gitbash
 ssh-keygen -t rsa -C "premprakashrohan@gmail.com"
 ssh-add id_rsa
Error:Could not open a connection to your authentication agent.
 eval `ssh-agent -s`
 ssh-add id_rsa


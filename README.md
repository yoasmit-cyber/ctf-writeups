# BANDIT WRITEUPS
works in BANDITGAMES
-->level 0 - 1

to find the pass for level 1, log in through ssh connection
bash :
 $ ssh bandit0@bandit.labs.overthewire.org -p 2220
pass : bandit0

searched what is in the directory using 'ls'
found : readme
used cat
bash : 
  $ cat readme
found the pass for level 1 which is : 6y2kwnwK6grgvwvpvLaa2T1cpFEKOhNR

--> level 1-2
bash : 
  $ ssh bandit1@bandit.labs.overthewire.org -p 2220
use the pass found : 6y2kwnwK6grgvwvpvLaa2T1cpFEKOhNR

log in and then type ls to show the contents of the directory 
this will show a file named "-"
while trying to use cat you wll realize that you will not able to open the file
okay to open it use the direct path 
bash 
  $ cat ./"file_name"
here 
  $ cat ./-
you will then get the password for level 2

--> level 2-3





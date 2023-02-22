#!/bin/bash
su betty                                                                                                                                                 
whoami                                                                                                                                                   
groups                                                                                                                                                   
sudo chown betty hello                                                                                                                                   
touch hello                                                                                                                                              
sudo chmod u+x hello                                                                                                                                     
sudo chmod 754 hello                                                                                                                                     
chmod ugo+x hello 
chmod 007 hello
chmod 753 hello
chmod --reference olleh hello
chmod -R a+X ./
mkdir -m 751 my_dir
chgrp school hello
sudo chown -R vincent:staff .
sudo chown -h vincent:staff _hello
chown --from=guillaume betty hello
telnet towel.blinkenlights.nl

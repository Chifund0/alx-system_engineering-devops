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

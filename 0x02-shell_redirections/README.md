#!/bin/bash
echo “Hello, World”
echo "\"(Ôo)'"
cat /etc/passwd
cat /etc/passwd /etc/hosts
tail -n 10 /etc/passwd
head -n 10 /etc/passwd
head -n 3 iacta | tail -n 1
echo -e "Best School"  >> "\\*\\\\'\"Best School\"\\'\\\\*$\\?\\*\\*\\*\\*\\*:)"
ls -la > ls_cwd_content
tail -1 iacta >> iacta
find . -type f -name *.js -delete
find -mindepth 1 -type d | wc -l
ls -t | head -n 10
sort | uniq u
egrep root /etc/passwd
egrep -c bin /etc/passwd
egrep -A 3 root /etc/passwd
egrep -v bin /etc/passwd
egrep ^[[:alpha:]] /etc/ssh/sshd_config
tr Ac Ze
tr -d Cc
rev
cut -f 1,6 -d : /etc/passwd | sort
find . -empty -printf "%f\n"
find . -type f -iname '*.gif' -printf '%f\n' | sed 's/\.gif$//' | LC_COLLATE=C sort -f
echo "$(cut -c 1 | tr -d '\n')"
tail -n +2 | cut -f 1 | sort | uniq -c | sort -nr | head -11 | cut -c 9- 

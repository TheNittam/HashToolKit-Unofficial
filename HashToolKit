#!/usr/bin/bash

#Decrypt md5, sha1, sha256, sha384, sha512 hashes easily with terminal.
#Save this file to your /usr/local/bin/ as "hashtoolkit" without any extension.
#Usage: hashtoolkit <hash>

#Author : #Nittam | @TheNittam | https://nirmaldahal.com.np

curl -s https://hashtoolkit.com/decrypt-hash/?hash=$1 | grep -oP "(?<=<code>)(.*?)(?=<\/code>)" | tail -1

# linux-pla


## Create User:
adduser <username>
password: <super secure password>
##SSH Key :
generate key: ssh-keygen
id_rsa, id_rsa.pub
mkdir .ssh on remote machine
vi authorised-keys
paste getrated pub key to this file
## Add Permission:
chmod 700 ..ssh
chmod 600 authorised-keys

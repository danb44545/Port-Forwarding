# Port-Forwarding

from your kali box do this..
in one terminal type:
ssh -L 8080:10.1.1.223:3389 billy@10.10.10.55

then in another terminal type
rdesktop 127.0.0.1:8080

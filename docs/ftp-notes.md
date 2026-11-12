The control channel (port 21) carries short text commands and replies. When a file or directory listing needs to
move, a separate data channel opens. We use passive mode: the server opens a port in a range we choose
(40000 to 40100 in our lab) and the client connects to it. Passive mode works well through firewalls and NAT.

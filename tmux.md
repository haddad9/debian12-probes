## TMUX use socket
- Fork the read-write operation, tmux utilize unix domain socket, [UnixDomainSocket](https://medium.com/swlh/getting-started-with-unix-domain-sockets-4472c0db4eb1)
- open a connection so anybody has the access to the socket can operate the related tmux session
- Each socket is saved inside /tmp/tmux-[ID] whewhere ID is related to the unix user. 
- User can only access access the socket that the has the permission to, change the permission or grant access to another user using `chmod` if you want to share the sessession.
- Connect to another user's tmux session: `sudo tmux -S /tmp/tmux-1007/default attach`

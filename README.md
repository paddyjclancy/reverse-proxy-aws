
# User Set-up

This repo demonstrates the ability to utilize a reverse proxy, which can assist in load balancing by redirecting ports for the host, and abstracting HTTPS commands.


1) Clone repo
2) `cd ~/.ssh`
3) `$ ssh -i Eng57PatrickC.pem ubuntu@[IPv4 Public IP]`
4) `$ cd /home/ubuntu/app`
5) `$ pm2 start app.js`
6) Test development.local:3000/
7) Test development.local/
8) Test /posts, /fibonacci:n
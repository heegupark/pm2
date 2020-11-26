# pm2

# start
`pm2 start --name=[service name] "[start cmd]"`

# restart
`pm2 restart [name] or [pid]`

# list
`pm2 list`

# stop
`pm2 stop [name] or [pid]`

# delete(kill)
`pm2 delete [name] or [pid]`

# reboot when startup
1. `pm2 startup`
2. type the result of 1 in cmd. ex) `sudo env PATH=$PATH:/home/ubuntu/.nvm/versions/node/v14.2.0/bin /home/ubuntu/.nvm/versions/node/v14.2.0/lib/node_modules/pm2/bin/pm2 startup systemd -u ubuntu --hp /home/ubuntu`
3. `pm2 save`

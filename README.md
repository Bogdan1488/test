## How to make it work

Log in your serv (via Putty)

Change directory to home ``` cd ~ ``` or /home/username
```
git init
git clone https://github.com/Bogdan1488/test.git
cd test
sudo npm install
DEBUG=bridge
```
if needed ```sudo npm install pm2 -g``` [pm2 documentation](https://github.com/Unitech/pm2)

Run server ```pm2 bin/www```

# GiveawayBot™
[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)

### A Discord Giveaway bot written in Discord.js to create & enjoy Feature rich and Seamless Giveaways within your very own Discord guild!
## Links

> ⚠  This bot needs a [Node.js v16+](https://nodejs.org/en/blog/release/v16.0.0/)  runtime to function since discord.js version 13 requires said node version to function.
**Aliter**

### Step 1: Install the Dependencies:
Linux 
```sh
apt install nodejs npm -y
curl -sL https://deb.nodesource.com/setup_16.x -o nodesource_setup.sh
chmod 777 nodesource_setup.sh
./nodesource_setup.sh
apt install nodejs -y
npm install

```
Windows 
```sh
# https://nodejs.org/en/blog/release/v16.0.0/ get node.js
npm install 
```

### Step 2: Obtain a Bot Token From [Here](https://discord.com/developers) <br> <br>
<kbd>
  <img src="https://zerosnap.000webhostapp.com/2faykzzg.gif">
</kbd>
<b>
  

### Step 3 : Replace the Token in [config.json](https://github.com/ZeroDiscord/Giveaway/blob/master/config.json) <br>
#### That's all! We Are Done! Now Simply host the Bot!

### Run with node
```sh
node index.js
```
### Run with pm2
```sh
npm install -g pm2@latest
pm2 start --name "Giveaway" index.js --watch
```

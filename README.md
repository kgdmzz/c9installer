# c9installer

# c9userpw
admin:admin

# Cloud9 Auto Installer

Requirements

  - Ubuntu (14 > 20 LTS)
  - SSH Access
  - Port 8080

# Installation
Then run the installer command
```sh
$ sudo apt-get install curl -y && sudo apt-get install git -y && git clone https://github.com/kgdmzz/c9installer && cd c9installer && bash c9installer.sh && sudo forever start ~/c9sdk/server.js -w /var/badut --port 8080 --listen 0.0.0.0 --auth admin:admin
```

### Now open you browser and visit http://your.ip.address:8080
enter username and password when prompted. Yey! your personal cloud IDE is installed.

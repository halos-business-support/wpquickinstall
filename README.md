# wpquickinstall

<h1>About</h1>

Welcome to the Halos Business Support Github Account. This repository contains code for
installing Apache, MariaDB, PHP and Wordpress on virgin Ubuntu Servers. It was originally designed for 
use on Ubuntu 20.04 LTS on AWS but may work with other flavours. This collection of scripts will do the following. 

1. Install Apache, MariaDB and PHP
2. Install Wordpress
3. Setup your apache Vhosts
4. Install Lets Encrypt Certbot and issue an SSL Certificate.

Developed by Steven Duval at Halos Business Support. If you need support for your business, why not check us out. 
**https://halos.support**. 

<h2>Getting Started</h2>

Start by cloning the repository to your server.

`git clone https://github.com/halos-business-support/wpquickinstall.git`

Navigate to the wpquickinstall directory and then to make your scripts executable. 

`sudo chmod +x *.sh`

Now you have 4 scripts to choose from. 

- **Install Apache Server, Maria DB and PHP** > lampinstall.sh
- **Download Wordpress and Setup DB** > wpinstall.sh
- **Set Up Apache Vhosts** > vhostinstall.sh
- **Install Lets Encrypt Certbot and issue an SSL Certificate** > certbotinstall.sh

<h2>Running Your Scripts</h2>

To run your scripts just enter the following and follow the onscreen instructions: 
`sudo ./"SCRIPTNAME"`

<h2>Further Development</h2>

At some point I'll add a "**beast mode**" which will run all 4 scripts one after the other with one singular user input at the start. 
This will probably require a little bit more testing first. 


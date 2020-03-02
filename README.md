==============================================================================================================================================
STUFF

ADOBE PHOTOSHOP  1045-1656-1984-6490-9561-5688

http://127.0.0.1:8000/register?next=/

Important links

Datascience Concepts

https://t.co/zfWgEfyA8d?amp=1

https://t.co/SQamq5CSRQ?amp=1

https://github.com/jakevdp/PythonDataScienceHandbook/tree/master/notebooks
Cybersecurity
[7:01 PM, 3/28/2019] Anthony - CEH: https://katcr.co/torrent/364470/udemy-practice-your-first-penetration-test-kali-amp-metasploit-lab.html
[7:02 PM, 3/28/2019] Anthony - CEH: https://monova.to/167CEE868BB34A178B72B530BE27CD98EFBE0688
[7:03 PM, 3/28/2019] Anthony - CEH: https://katcr.co/torrent/307838/udemy-ethical-hacking-with-metasploit-the-penetration-testing-tool.html

Applying for Attachment:
Data Science    https://okhi.recruiterbox.com/jobs/fk0j7cr/
Cybersecurity   https://www.un-yk.com/
Freelance       Appwork
Fitness         https://www.youtube.com/watch?v=3p8EBPVZ2Iw    

*********************************************************************
0713835028*

<a href="mailto:dancunmanyinsait@gmail.com" target="_blank">
                       Email: dancunmanyinsait@gmail.com
                    </a>

web: gunicorn waweru.wsgi --log-file -


*********************************************************************

==================================

PHONE BACKUP

https://findmymobile.samsung.com
serial number:RZ8M10REVSJ
IMEI:358147090839744

KRA engineerDan@1234
SAF @@aUrsAP@w9x.j@
http://portal.jkuat.ac.ke/Home/Index
=================================

GRUB RESCUE ERROR FIX

sudo update-grub2
sudo grub-install /dev/sda

sudo add-apt-repository -y ppa:yannubuntu/boot-repair
sudo apt-get update
sudo apt-get install -y boot-repair && boot-repair

=================================

REMOVE

sudo rm -rf 

=================================

FIX FLASH ON UBUNTU TERMINAL 

sudo fdisk -l

1st option
sudo mkfs.msdos -f 32 /dev/sdb
DEFRAGMENT sudo e4defrag /dev/sda7

2nd option
udisksctl power-off -b /dev/sdb

FIX FLASH ON WINDOWS TERMINAL 
diskpart
list disk
attributes disk
attributes disk clear diskonly
exit



=================================
UBUNTU TRANSPARENCY(MENU BAR AND TAB)
Install (Dynamic Panel Transparency ) in ubuntu softwares
-------------------------------------------
gsettings set org.gnome.shell.extensions.dash-to-dock transparency-mode 'FIXED'
gsettings set org.gnome.shell.extensions.dash-to-dock background-opacity 0.2
-------------------------------------------
Install  dash-dock extension 


===============================================================================================================================================


			<---NETWORKS--->

Assigning static ip address to the local network

sudo ifconfig enp9s0 192.168.92.5 netmask 255.255.0.0
sudo route add default gw 192.168.92.1 enp9s0
ping 192.168.92.5

Assigning dynamic ip address to the local network

sudo dhclient enp9s0
----------------------------------------------------------
DHCP

sudo apt install isc-dhcp-server
sudo nano /etc/dhcp/dhcpd.conf

EDIT THIS FILE
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
default-lease-time 600;
max-lease-time 7200;

dns-update-style none;

authoritative;

subnet 192.168.92.0 netmask 255.255.255.0{
	range 192.168.92.0 192.168.92.100;
	option routers 192.168.91.1;
	option subnet-mask 255.255.255.0;
	option domain-name-servers 192.168.92.1, 8.8.8.8;
}

host Windows7{
	hardware ethernet 00:0c:29:e6:75:b9;
	fixed-address 192.168.92.1;
}
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
sudo systemctl restart isc-dhcp-server
sudo systemctl status isc-dhcp-server


===============================================================================================================================================


nmcli connection add con-name 'Ethernet' ifname enp9s0 type ethernet 

sudo netdiscover 
rfkill 

sudo service NetworkManager start
sudo service NetworkManager stop 

MICROTIK
startx
service gdm3 restart 

			<---SYSTEM--->


(PHONE)TERMUX

pkg install lynx
termux-setup-storage


(PC)
			
Set flash sudo users

sudo adduser dan vboxusers
-------------------------------------------
Set up ssh on host machine

1st)Assigning static ip address to the local network

2nd)

sudo apt install ssh

Performing ssh

ssh pentester@127.0.0.1

       0R   USING PASSWORD
sudo ssh pentester@127.0.0.1 -p 2000

sudo service ssh status

       OR   USING KEYS
ssh-keygen
cat ~/.ssh/id_rsa.pub | ssh pentester@127.0.0.1 -p 2000 "mkdir -p ~/.ssh && chmod 700 ~/.ssh && cat >> ~/.ssh/authorized_keys"
ssh pentester@127.0.0.1 -p 2000

--------------------------------------------
Set up ssh on virtual machine
++++++++++++++++++++++++++++
sudo nano /etc/network/interfaces

EDIT THIS FILE
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
#This file describes the network interfaces availableon your system and how to activate them....
source /etc/network/interfaces.d/*

#The loopback network interface
auto lo
iface lo inet loopback

auto eth1 
iface eth1 inet static
	address 192.168.92.10
	netmask 255.255.255.0
	broadcast 192.168.92.255
	network 192.168.92.0
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

++++++++++++++++++++++++++++++
sudo nano /etc/ssh/ssh_config
sudo nano /etc/ssh/sshd_config
adduser pentester
adduser pentester sudo
service sshd status
service ssh status

++++++++++++++++++++++++++++++++++++++
Performing ssh

systemctl enable ssh.service
service ssh start

++++++++++++++++++++++++++
loginctl list-sessions 
loginctl terminate-session 
++++++++++++++++++++++++++

NETWORK ADMIN
https://medium.com/@adinika.15/installing-active-directory-on-windows-server-2012-r2-e9e614770588
===============================================================================================================================================

			<---CYBER SECURITY--->


===============================================================================================================================================

			<---SOFTWARE(ARTIFICIAL INTELLIGENCE && QUANTUM SCIENCE)--->

*********************************************************************
					    			PREREQUISITES
*********************************************************************
STATIC TYPING PYTHON

Install mypy 
 python3 -m pip install -U mypy'
 mypy example.py

-------
PYTHON
Install python dev    sudo apt-get install build-essential libssl-dev libffi-dev python3-dev
Install pip3          sudo apt install python3-pip

-------
RUST
Install  Rust and Cargo   check online
Rustenv
Install _ONCE_            pip install rustenv
Create                    rustenv  renv
Activate                  ./renv/bin/activate
Deactivate                deactivate_rustenv
-------
VIRTUAL ENV  


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
OLD Python env

            _ONCE_ 1st)Install   sudo apt-get install python3-venv 
                   2nd)Create    virtualenv -p /usr/bin/python3.7 venv
Activate env:      source venv/bin/activate 
Install pip/pip3 _ONCE_    curl https://bootstrap.pypa.io/get-pip.py | python
Installation of dep        pip3 install -r requirements.txt
                           pip3 install -r requirements.txt --upgrade
Deactivate                 deactivate
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
NEW Python env

Install pip3 _ONCE_    sudo apt install python3-pip

Install _ONCE_             pip install pipenv
*************************
$ which python3.7
*************************
Create                    pipenv --python /usr/bin/python3.7
Activate                  pipenv shell
Installation of dep       pipenv install -r requirements.txt
Upgrade dep               pipenv install -r requirements.txt --upgrade
Deactivate                deactivate
       


Effect changes:            python3 manage.py makemigrations
                           python3 manage.py migrate
                           python3 manage.py runserver

------------------
Personal github 4f41ea34f379e4e0dc151e6964c6468f4807e3c5
------------------
DEMONSTRATION

sudo apt install kazam

On how to use Kazam Screencaster https://www.youtube.com/watch?v=ADPPpY6ZEI8
------------------

HEROKU  ((( H - Conard@92 )))


web: gunicorn waweru.wsgi --log-file -

*********************************************************************
sudo snap install --classic heroku

wget -qO- https://toolbelt.heroku.com/install-ubuntu.sh | sh



Collectstatic error while deploying Django app to Heroku

1 disable the collectstatic during a deploy

$ heroku config:set DISABLE_COLLECTSTATIC=1

2 deploy

$ git push heroku master

3 run migrations (django 1.10 added at least one)

$ heroku run python3 manage.py migrate

4 run collectstatic using bower

$ heroku run 'bower install --config.interactive=false;grunt prep;python3 manage.py collectstatic --noinput'

5 enable collecstatic for future deploys

$ heroku config:unset DISABLE_COLLECTSTATIC

6 try it on your own (optional)

$ heroku run python manage.py collectstatic


---------------------------------------------------------------------------------------------------------
Pyinstaller

pyinstaller --onedir --onefile --name=passwordlocker --windowed "/home/dan/PycharmProjects/dancunmanyinsa/manage.py"


---------------------------------------------------------------------------------------------------------
GIT COLLABORATION Link http://adzumi.co.ke/blog/github_contribution

As a new developer, contributing to a project can be scary. I get it,  I was there too. It took me way too long to make my first Pull Request.

Contributing is also a great way to learn more about social coding on Github, new technologies and their ecosystems and how to make constructive, helpful bug reports, feature requests and the noblest of all contributions.

STEP 1: SET UP A WORKING COPY ON YOUR COMPUTER
First of all, you need a local fork of the project, so go ahead and press the “fork” button on GitHub. This will create a copy of the repository in your own GitHub account and you’ll see a note that it’s been forked underneath the project name:



Now you need a copy locally, so find the clone URL in the right-hand column and use that to clone locally using a terminal:

$ git clone https://github.com/lawrence254/StudentEngagement.git
Which will do something like this:



Now navigate to the project's directory:

$ cd StudentEngagement
Finally, in this stage, you need to set up a new remote that points to the original project so that you can grab any changes and bring them into your local copy. Firstly click on the link to the original repository, it’s labeled “Forked from” at the top of the GitHub page. This takes you back to the projects main GitHub page, so you can find the Clone URL and use it to create the new remote, which we’ll call upstream.

$ git remote add upstream https://github.com/lawrence254/StudentEngagement.git
You now have two remotes for this project on disk:

origin which points to your GitHub fork of the project. You can read and write to this remote.
upstream which points to the main project’s GitHub repository. You can only read from this remote.
STEP 2: MAKE SOME CHANGES
This is the fun bit where you get to contribute to the project. The number one rule is to put each piece of work on its own branch. If the project is using git-flow, then it will have both a master and a development branch. The general rule is that if you are adding a new feature then branch from development. If the project only has a master branch, the branch from that. 

For this example, the forked repository had a number of branches already, one of them called 'lawrence'. This is the branch the owner of the repository has been working on. We’ll assume we’re adding a feature in StudentEngagement, so we branch to that branch:

$ git checkout lawrence
$ git pull upstream lawrence && git push origin lawrence
Firstly we ensure we’re on the master branch. Then the git pull command will sync our local copy with the upstream project and the git push syncs it to our forked GitHub project. Finally, we checkout to the 'lawrence' branch. 

Now you can add a feature(Or fix a bug).

If the project has tests, run them to ensure you haven’t broken anything. You may also add a new test to show that your change fixes the original problem.

STEP 3: CREATE A PULL REQUEST
To create a Pull Request you need to push your branch to the origin remote and then press some buttons on GitHub.

To push the new branch:

$ git push origin lawrence
Now swap back to the browser and navigate to your fork of the project (https://github.com/YomZsamora/StudentEngagement in my case) and you’ll see that the branch is listed at the top with a handy “Compare & pull request” button:



Go ahead and press the button! 

On this page, ensure that the “base fork” points to the correct repository and branch. Then ensure that you provide a good, succinct title for your pull request and explain why you have created it in the description box. Add any relevant issue numbers if you have them.



If you scroll down a bit, you’ll see a diff of your changes. Double check that it contains what you expect.

Once you are happy, press the “Create pull request” button and you’re done.

For your work to be integrated into the project, the maintainers will review your work and either request changes or merge it.

To Summarize
That’s all there is to it. The fundamentals are:

Fork the project & clone locally.
Create an upstream remote and sync your local copy.
Ensure you're working on the correct branch.
Do the work, write good commit messages and read the CONTRIBUTING file if there is one.
Push to your origin repository.
Create a new Pull Request in GitHub.

------------------------------------------------------------------------------------------------------------


*********************************************************************
						DIGITAL COMPUTATION

*********************************************************************
++++++++++++++++++++++
WEKA DATA SCIENCE SOFTWARE
 cd weka-3-8-3/
 java -jar weka.jar
 

INSTALLING ANACONDA


cd /tmp
sudo apt install curl
curl -O https://repo.anaconda.com/archive/Anaconda3-2019.03-Linux-x86_64.sh
sha256sum Anaconda3-2019.03-Linux-x86_64.sh
bash Anaconda3-2019.03-Linux-x86_64.sh
conda list
conda update conda
conda update anaconda

+++++++++++++++++++++

cd anaconda3/
source $HOME/anaconda3/bin/activate
conda list
conda update conda
+++++++++++++++++++++




This tutorial will guide you through installing the Python 3 version of Anaconda on a Debian 10 server.

Prerequisites
Before you begin with this guide, you should have a non-root user with sudo privileges set up on your server.

You can achieve this prerequisite by completing our Debian 10 initial server setup guide.

Installing Anaconda
To install Anaconda on a Debian 10 server, you should download the latest Anaconda installer bash script, verify it, and then run it.

Find the latest version of Anaconda for Python 3 at the Anaconda Distribution page. At the time of writing, the latest version is 2019.03, but you should use a later stable version if it is available.

Next, change to the /tmp directory on your server. This is a good directory to download ephemeral items, like the Anaconda bash script, which we won’t need after running it.

cd /tmp
We’ll use the curl command-line tool to download the script. Install curl:

sudo apt install curl
Now, use curl to download the link that you copied from the Anaconda website:

curl -O https://repo.anaconda.com/archive/Anaconda3-2019.03-Linux-x86_64.sh
At this point, we can verify the data integrity of the installer with cryptographic hash verification through the SHA-256 checksum. We’ll use the sha256sum command along with the filename of the script:

sha256sum Anaconda3-2019.03-Linux-x86_64.sh
You’ll receive output that looks similar to this:

Output
45c851b7497cc14d5ca060064394569f724b67d9b5f98a926ed49b834a6bb73a  Anaconda3-2019.03-Linux-x86_64.sh
You should check the output against the hashes available at the Anaconda with Python 3 on 64-bit Linux page for your appropriate Anaconda version. As long as your output matches the hash displayed in the sha2561 row, you’re good to go.

Now we can run the script:

bash Anaconda3-2019.03-Linux-x86_64.sh
You’ll receive the following output:

Output

Welcome to Anaconda3 2019.03

In order to continue the installation process, please review the license
agreement.
Please, press ENTER to continue
>>> 
Press ENTER to continue and then press ENTER to read through the license. Once you’re done reading the license, you’ll be prompted to approve the license terms:

Output
Do you approve the license terms? [yes|no]
As long as you agree, type yes.

At this point, you’ll be prompted to choose the location of the installation. You can press ENTER to accept the default location, or specify a different location to modify it.

Output
Anaconda3 will now be installed into this location:
/home/sammy/anaconda3

  - Press ENTER to confirm the location
  - Press CTRL-C to abort the installation
  - Or specify a different location below

[/home/sammy/anaconda3] >>> 
The installation process will continue. Note that it may take some time.

Once installation is complete, you’ll receive the following output:

Output
...
installation finished.
Do you wish the installer to initialize Anaconda3
by running conda init? [yes|no]
[no] >>> 
Type yes so that you do not need to add Anaconda to the PATH manually.

Output
Appending source /home/sammy/anaconda3/bin/activate to /home/sammy/.bashrc
A backup will be made to: /home/sammy/.bashrc-anaconda3.bak
...
You can now activate the installation by sourcing the ~/.bashrc file:

source ~/anaconda3/bin/activate
You will now be in Anaconda’s base programming environment that is automatically named base. Your prompt will change to reflect this.


Now, you can run the conda init command to initialize your environment.

conda init
Once you have done that, you can verify your install by making use of the conda command, for example with list:

conda list
You’ll receive output of all the packages you have available through the Anaconda installation:

Output
# packages in environment at /home/sammy/anaconda3:
#
# Name                    Version                   Build  Channel
_ipyw_jlab_nb_ext_conf    0.1.0                    py37_0  
alabaster                 0.7.12                   py37_0  
anaconda                  2019.03                  py37_0  
...
Now that Anaconda is installed, we can go on to setting up Anaconda environments.

Setting Up Anaconda Environments
Anaconda virtual environments allow you to keep projects organized by Python versions and packages needed. For each Anaconda environment you set up, you can specify which version of Python to use and can keep all of your related programming files together within that directory.

First, we can check to see which versions of Python are available for us to use:

conda search "^python$"
You’ll receive output with the different versions of Python that you can target, including both Python 3 and Python 2 versions. Since we are using the Anaconda with Python 3 in this tutorial, you will have access only to the Python 3 versions of packages.

Let’s create an environment using the most recent version of Python 3. We can achieve this by assigning version 3 to the python argument. We’ll call the environment my_env, but you’ll likely want to use a more descriptive name for your environment especially if you are using environments to access more than one version of Python.

conda create --name my_env python=3
We’ll receive output with information about what is downloaded and which packages will be installed, and then be prompted to proceed with y or n. As long as you agree, type y.

The conda utility will now fetch the packages for the environment and let you know when it’s complete.

You can activate your new environment by typing the following:

conda activate my_env
With your environment activated, your command prompt prefix will change:


Within the environment, you can verify that you’re using the version of Python that you had intended to use:

 python --version
Output
Python 3.7.3
When you’re ready to deactivate your Anaconda environment, you can do so by typing:

conda deactivate
To target a more specific version of Python, you can pass a specific version to the python argument, like 3.5, for example:

conda create -n my_env35 python=3.5
You can update your version of Python along the same branch within a respective environment with the following command:

conda update python
If you would like to target a more specific version of Python, you can pass that to the python argument, as in python=3.3.2.

You can inspect all of the environments you have set up with this command:

conda info --envs
Output
# conda environments:
#
base                  *  /home/sammy/anaconda3
my_env                   /home/sammy/anaconda3/envs/my_env
my_env35                 /home/sammy/anaconda3/envs/my_env35

The asterisk indicates the current active environment.

Each environment you create with conda create will come with several default packages:

openssl
pip
python
readline
setuptools
sqlite
tk
wheel
xz
zlib
You can add additional packages, such as numpy for example, with the following command:

conda install --name my_env35 numpy
If you know you would like a numpy environment upon creation, you can target it in your conda create command:

conda create --name my_env python=3 numpy
If you are no longer working on a specific project and have no further need for the associated environment, you can remove it. To do so, type the following:

conda remove --name my_env35 --all
Now, when you type the conda info --envs command, the environment that you removed will no longer be listed.






*********************************************************************
						ANALOGUE COMPUTATION

*********************************************************************


django-admin startproject heyapp ->VIEWS
django-admin startproject heyapp .  ->WSGI
 


DJANGO && SERVICE WORKER
from django.views.generic import TemplateView

urlpatterns = [
  url(r'^sw.js', (TemplateView.as_view(template_name="sw.js", content_type='application/javascript', )), name='sw.js'),
]


DJANGO && MONGODB CONNECTION

1)django_mongodb_engine
2)djongo -> transpiler you write sql queries and it transpiles to mongo nosql queries

1)django_mongodb_engine ->check https://django-mongodb-engine.readthedocs.io/en/latest/topics/setup.html
Django-nonrel, a fork of Django that adds support for non-relational databases
Djangotoolbox, a bunch of utilities for non-relational Django applications and backends
Django-nonrel
pip install git+https://github.com/django-nonrel/django@nonrel-1.5
Djangotoolbox
pip install git+https://github.com/django-nonrel/djangotoolbox
Django MongoDB Engine
You should use the latest Git revision.

pip install git+https://github.com/django-nonrel/mongodb-engine
Configuration
Database setup is easy (see also the Django database setup docs):

DATABASES = {
   'default' : {
      'ENGINE' : 'django_mongodb_engine',
      'NAME' : 'my_database'
   }
}
Django MongoDB Engine also takes into account the HOST, PORT, USER, PASSWORD and OPTIONS settings.

Possible values of OPTIONS are described in the settings reference.



2)djongo ->check https://pypi.org/project/djongo/
Install djongo:

pip install djongo
Into settings.py file of your project, add:

DATABASES = {
     'default': {
         'ENGINE': 'djongo',
         'NAME': 'your-db-name',
     }
 }
Run (ONLY the first time to create collections in mongoDB):

manage.py makemigrations
manage.py migrate
YOUR ARE SET! HAVE FUN!

Requirements
Djongo requires python 3.6 or above.
How it works
Djongo is a SQL to mongodb query transpiler. It translates a SQL query string into a mongoDB query document. As a result, all Django features, models etc work as is.

Django contrib modules:

'django.contrib.admin',
'django.contrib.auth',
'django.contrib.sessions',
and others… fully supported.

Important links
Full Documentation
Source code


DJANGO && POGRESQL CONNECTION 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'portfolio',
        'USER':'dan',
        'PASSWORD':'phoenix',
		'HOST':'127.0.0.1',
        'PORT':'5432',
    }
}

     SMTP IN DJANGO 

	 SETTINGS.PY

EMAIL_BACKEND = ‘django.core.mail.backends.smtp.EmailBackend’
EMAIL_HOST = ‘smtp.gmail.com’
EMAIL_USE_TLS = True
EMAIL_PORT = 587
EMAIL_HOST_USER = ‘your_account@gmail.com’
EMAIL_HOST_PASSWORD = ‘your account’s password’

        ((( OR )))
		
EMAIL_BACKEND = "django.core.mail.backends.smtp.EmailBackend"
EMAIL_HOST = "smtp.gmail.com"
EMAIL_USE_SSL = True
EMAIL_PORT = 465
EMAIL_HOST_USER = "your_account@gmail.com"
EMAIL_HOST_PASSWORD = "your account’s password"
  
  VIEWS.PY

import django
from django.core.mail import send_mail
from django.conf import settings

def email(request):
    subject = 'Thank you for registering to our site'
    message = ' It is great choosing to work with a team of perfectionists'
    email_from = settings.EMAIL_HOST_USER
    recipient_list = ['receiver@gmail.com',]
    send_mail( subject, message, email_from, recipient_list )
    return redirect('redirect to a new page')



%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&
===========================================================
WINDOWS AND UBUNTU
sudo systemctl enable postgresql
sudo service postgresql restart

Connect to postgres:                  sudo -i -u postgres

-------------------------------------------------

psql

CREATE DATABASE myproject;

CREATE USER myprojectuser WITH PASSWORD 'password';

ALTER ROLE myprojectuser SET client_encoding TO 'utf8';
ALTER ROLE myprojectuser SET default_transaction_isolation TO 'read committed';
ALTER ROLE myprojectuser SET timezone TO 'UTC';

GRANT ALL PRIVILEGES ON DATABASE myproject TO myprojectuser;

--------------------------------------------------

Get current info:                     \conninfo


Postgresql commands
List all databases: \l.
Exit out of help menu: \q
Connect to database: \c database_name
List tables in current database: \dt
List columns in a table: \d table_name
See a list of all psql commands: \? (Press the down arrow to scroll through, or q to exit list.)
exit

######################################################## 
FORGOTTEN PASSWD/ SET NEW PASSWD ON POSTGRES
sudo -i -u postgres 
could not change directory to "/root"
psql (9.1.11)
Type "help" for help.

postgres=# \password
Enter new password:
Enter it again:
postgres=# \q
#########################################################

-------------------------------------------------------------------

INSTALL POSTGRESQL  -> https://linuxconfig.org/install-postgresql-on-ubuntu-18-04-bionic-beaver


sudo apt install postgresql-client
sudo apt install postgresql
 * Restart my pc then on the terminal *
sudo systemctl enable postgresql
sudo service postgresql restart

WINDOWS FIX FORPOSTGRES CONFIGURATION 

By default the PostgreSQL server will listen only on a local loop-back interface 127.0.0.1. If you need to configure your PostreSQL server to listen on all networks you will need to configure its main configuration file /etc/postgresql/10/main/postgresql.conf:
$ sudo nano /etc/postgresql/10/main/postgresql.conf
and add the following line somewhere to the CONNECTIONS AND AUTHENTICATION section:
listen_addresses = '*'

sudo service postgresql restart

&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&

PGADMIN INSTALLATION
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
sudo apt-get install virtualenv python3-pip libpq-dev python3-dev

cd
Create env:   virtualenv -p python3 pgadmin4
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
cd pgadmin4
source bin/activate
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
pip3 install https://ftp.postgresql.org/pub/pgadmin/pgadmin4/v4.2/pip/pgadmin4-4.2-py2.py3-none-any.whl

Configure
Override default paths and set it to single-user mode in the local configuration file:

For Python2.x
nano lib/python2.7/site-packages/pgadmin4/config_local.py

For Python3.x
nano lib/python3.6/site-packages/pgadmin4/config_local.py

Write:

import os
DATA_DIR = os.path.realpath(os.path.expanduser(u'~/.pgadmin/'))
LOG_FILE = os.path.join(DATA_DIR, 'pgadmin4.log')
SQLITE_PATH = os.path.join(DATA_DIR, 'pgadmin4.db')
SESSION_DB_PATH = os.path.join(DATA_DIR, 'sessions')
STORAGE_DIR = os.path.join(DATA_DIR, 'storage')
SERVER_MODE = False
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
python3 lib/python3.6/site-packages/pgadmin4/pgAdmin4.py
,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,
(Browser URL + PORT)
name                            DB1
connection(host name/addrress)  127.0.0.1
username                        postgres
passwd                          phoenix
,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,
deactivate

----------------------------------------------------------------------------------------------------------
Flask Application structure

|-Watchlist
    |-app/
        |-main/
            |-__init__.py
            |-errors.py
            |-forms.py
            |-views.py
        |-static/
        |-templates/
        |-__init__.py
        |-models.py
        |-requests.py
    |-tests/
        |-test_movie.py
        |-test_review.py
    |-virtual/
    |-config.py
    |-.gitignore
    |-manage.py
    |-start.sh
 
-----------------------------------------------------------------------------------------------------------
Flask
  
  pip install flask
  curl https://bootstrap.pypa.io/get-pip.py | python
  pip install flask-bootstrap
  python3.6 -m  pip install gunicorn
  sudo apt-get update
  sudo apt-get install postgresql postgresql-contrib libpq-dev
  pip install flask-migrate
  pip install flask-login
  pip install flask-uploads
  pip install flask-mail
  pip install flask-simplemde markdown2

------------------------------------------
Django
 pip install django==1.11
 pip install django-bootstrap4
 pip install psycopg2
 pip install python-decouple
 pip install django-registration==2.4.1
 pip install djangorestframework
 pip install django-progressive-web-app

--------------------------------------------------------------------------------------------------------


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


WINDOWS (UBUNTU TERMINAL)
+++++++++++++++++++++++++++++++++++++++ 
cd /mnt/c/Users/Dan/
cd /mnt/c/Users/Dan/Desktop/Projects/ow from any to any port 5432 proto tcp

UNINSTALL POSTGRESQL -> sudo apt-get --purge remove postgresql postgresql  postgresql-client  postgresql-client postgresql-client-common postgresql-common  postgresql-contrib postgresql-contrib


&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&

REMOVE OLD UBUNTUUPDATEFILES FROM /boot

sudo apt-get-clean

First, get the name of the kernel the system is currently running by using uname like this:

-----------------------------------------------
uname -sr
dpkg -l | grep linux-image | awk '{print$2}'
sudo apt-get purge linux-image-5.3.0-18-generic
sudo apt autoremove
-----------------------------------------------


Or if you use aptitude use this variant of the command:

sudo aptitude purge linux-image-x.x.x.1-generic


Make a note of that because that is the name of the current active kernel you don’t want to remove. Now knowing that, we need to figure out what the other—extraneous—kernels are


CREATING SWAP  AFTER LINUX INSTALLATION

In case you don't want or you're not sure how to create a swap partition, you can create a swap file which will work in the same way as partition. Here are the steps (using terminal):

Create an empty file (1K * 4M = 4 GiB).

sudo mkdir -v /var/cache/swap
cd /var/cache/swap
sudo dd if=/dev/zero of=swapfile bs=1K count=4M
sudo chmod 600 swapfile
Convert newly created file into a swap space file.

sudo mkswap swapfile
Enable file for paging and swapping.

sudo swapon swapfile
Verify by: swapon -s or top:

top -bn1 | grep -i swap
Should display line like: KiB Swap:  4194300 total,  4194300 free

To disable, use sudo swapoff swapfile command.

Add it into fstab file to make it persistent on the next system boot.

echo "/var/cache/swap/swapfile none swap sw 0 0" | sudo tee -a /etc/fstab
Re-test swap file on startup by:

sudo swapoff swapfile
sudo swapon -va



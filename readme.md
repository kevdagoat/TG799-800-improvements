This will fix the missing image problem when installing on a TG799 or TG800.

To install:
For TG799vac and TG800vac only!

Run on modem command line:

$ wget -P /tmp http://github.com/kevdagoat/TG799-800-improvements/blob/master/GUI.tar.bz2?raw=true 

$ bzcat /tmp/GUI.tar.bz2 | tar -C / -xvf -

$ /etc/init.d/rootdevice force

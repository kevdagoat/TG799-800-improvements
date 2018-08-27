This will fix the missing image problem when installing on a TG799 or TG800.

To install:
For TG799vac and TG800vac only!

Run on modem command line:

<b>Make sure to install ansuels GUI first as this is a patch only!</b>

$ wget -P /tmp http://github.com/kevdagoat/TG799-800-improvements/blob/master/GUI.tar.bz2?raw=true 

If This method doesn't work, copy the file over to the /tmp dir manually using something like WinSCP.

$ bzcat /tmp/GUI.tar.bz2 | tar -C / -xvf -

$ /etc/init.d/rootdevice force

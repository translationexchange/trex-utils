# Installing IE on Mac

First, make sure you have the VirtualBox installed locally. Visit https://www.virtualbox.org/wiki/Downloads and install the latest version.

Then run the following script from the command line to install IE 10:

    $ curl -s https://raw.githubusercontent.com/translationexchange/trex-utils/master/ievms.sh | IEVMS_VERSIONS='10' bash 
  
Then run the following script from the command line to install IE Edge:

    $ curl -s https://raw.githubusercontent.com/translationexchange/trex-utils/master/ievms.sh | env IEVMS_VERSIONS="EDGE" bash 
  
Finally, open the VirtualBox and run the IE you like


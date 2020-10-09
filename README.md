# zvsample
Quick Start Sample Application

Environment:
- Ubnuntu 16.04 LTS and 18.04 LTS Operating System 
- Internet Access

  . Enpoint Port 8080 open

The tar file is too big for GitHub.  To download the package, issue the following command from the Ubuntu Server

wget https://downloads.zerodownsoftware.com/zvsampled/zvsample-build.tar.gz

Unpack the file:  

tar xvzf zvsample-build.tar.gz

Run the Installation Script from elevated permissions

sudo ./install.sh


The Installation Script installs the zvsample application into the Ubuntu Server.  To start and stop the services,
the command:

sudo zvsample {start | stop | restart | status}

Application is accessed via port 8080, therefore, port 8080 needs to be opened to this deployment.

Authentication to Demo Account:   demo@demo.com/demo1234
Encryption Phrase:  1234

Restarting the software resets all data to the initial state of the image.  All data and changes will be lost.


History:

2020-10-7 Installation Support for both Ubuntu 16.04 and 18.04


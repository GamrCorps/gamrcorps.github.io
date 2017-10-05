#How to install Python 3.6.2 into a Cloud9 workspace
It feels very limiting sometimes that Cloud9 only lets you choose between Python 2.7 and 3.4.3. I personally am a Python 3.6.2 guy, so it would be very nice to have that option within Cloud9. This tutorial will quickly outline how to install Python 3.6.2 into a Cloud9 workspace.

##Setup
First, make sure that you have a [Cloud9](https://c9.io) account and workspace setup.
Next, inside the workspace, open a bash terminal. Run the command `lsb_release -a` and make sure that you are running a version of Ubuntu 14.04.X LTS. Here is what my console outputs when I run that command:

    gamrcorps:~/workspace $ lsb_release -a
    No LSB modules are available.
    Distributor ID: Ubuntu
    Description:    Ubuntu 14.04.5 LTS
    Release:        14.04
    Codename:       trusty

##Installation
Run the following commands in order:

 1. `sudo add-apt-repository ppa:jonathonf/python-3.6`
 2. `sudo apt-get update`
 3. `sudo apt-get install python3.6` (remember to press <kbd>Y</kbd> when prompted!)
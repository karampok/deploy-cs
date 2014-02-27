deploy-cs
=========

Helper script to provision VMs in our test evironment in Cloudstack, uses cloudstack-cli.

Installation
------------

    sudo gem install cloudstack-cli

    sudo git clone https://github.com/swisstxt/deploy-cs.git /usr/local/lib/deploy-cs
    sudo chmod +x /usr/local/lib/deploy-cs
    sudo ln -s /usr/local/lib/deploy-cs/deploy /usr/local/bin/deploy
    sudo ln -s /usr/local/lib/deploy-cs/destroy /usr/local/bin/destroy
    
    
Usage
-----

Create:

    /usr/local/bin/deploy node-bie-01

Remove:

    /usr/local/bin/destroy node-bie-01
    
    

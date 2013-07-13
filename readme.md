# About OpenStack
OpenStack is an Infrastructure as a Service (IaaS) cloud computing project that is free open source software released under the terms of the Apache License.  

The technology consists of a series of interrelated projects that control large pools of processing, storage, and networking resources throughout a datacenter, all managed through a dashboard that gives administrators control while empowering their users to provision resources through a web interface.

# Getting Started
The original guide for this project is [hosted on StackGeek](http://www.stackgeek.com/guides/gettingstarted.html).  You can also [view and fork the guide](https://gist.github.com/4042624) right here on Github.

Start your OpenStack setup by installing Ubuntu Server 12.04LTS on the servers you want included in your OpenStack cluster.  OpenStack can be installed on a single computer and nodes may be added at a later date to increase instance hosting capacity.

Login to your box via ssh and install *git* with *aptitude*. We'll become root and do an update first:

    aptitude update
    apt-get install -y git

Now checkout the StackGeek OpenStack setup scripts from Github:

    git clone git://github.com/StackGeek/openstackgeek.git
    cd openstackgeek/folsom


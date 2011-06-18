Overview
========

This is an updated implementation of the RAID EBS script available on quite a few sites.

Out of the box none ever worked properly.  

Requirements
============

Requirements for these two scripts are:

````ec2-api-tools
mdadm
xfsprogs
chef
knife-ec2
````

You may also need to install ruby-full and build-essentials

The following directories are assumed:

````
.ec2
.ssh
.chef
````

Assumptions:

* Chef and knife ec2 are installed on the system and configured properly in the project-dir
* You have a single node on your opscode or Chef standalone server


Configuration
=============

You'll need to run the initial script on your local machine which copies and executes the raid_setup script to your EC2 instance


Current
=======

The current configuration is for RAID10 and mongodb mounting to

`````
/var/lib/mongodb/
`````

This should be changed to fit your instance. The last five line fix the mongodb installation before restarting the service.

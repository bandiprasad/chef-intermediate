# Creating the Workstation

> An chef recipe that automates the creation of the workstation can be found in the [ChefDK Image](
https://github.com/chef-training/chefdk-image/blob/master/cookbooks/workstations/recipes/extending_cookbooks.rb
) project

* Installation of ChefDK

* Create a user named 'chef' with the password 'chef'

* Ensure the yum package repository is up-to-date

```
$ yum update -y
```

* Allow Password Authentication

* Disable the iptables service

* Disable SELINUX

* INSTALL various editors and tools that the participant will install: vim; emacs; nano; tree; and git.

* Clone the [Extending Cookbooks Repository](https://github.com/chef-training/extending_cookbooks-repo). This content is used during the second day of content and should be found in the day_2 folder.

* Install [Docker on CentOS](https://docs.docker.com/engine/installation/centos/)

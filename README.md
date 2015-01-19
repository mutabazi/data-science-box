Data Science Box
================

This virtual machine for performing data science is based on the virtual machine, data, scripts, and custom command-line tools used in the Data Science at the Command Line book, see also the [dsatcl git-repo](https://github.com/jeroenjanssens/data-science-at-the-command-line) and [site](http://datascienceatthecommandline.com).

# Requirements

Installation requires:
* [Vagrant](https://www.vagrantup.com)
* [VirtualBox](https://www.virtualbox.org)
* [Ansible](http://www.ansible.com/home)

# Installation
1. checkout the git repo
2. run *vagrant up*
3. and you are done! 

# Usage

Run:
* *./ipynb_server.sh* for the **IPython notebook server**
* *./ijunb_server.sh* for the **IJulia notebook server**
* *./irnb_server.sh* for the **IR notebook server**
* *./ipysh.sh* for the **IPython shell**
* *./wiki.sh* for the **Wiki**

The RStudio server can be reached via http://localhost:8787/ using the login: *vargrant* and passwrd: *vagrant*.

Note that the ds box is configured such that it automatically mounts the *~/Projects* folder. 

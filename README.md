# vagrant-xdebug
ABQ web geeks presentation

My IP address:  192.168.2.110

anonymous FTP, or webftp at 192.168.2.110:8081

## Why use local VMs for debugging?
* not secure to run on live web servers
* xdebug allows you to step through code, line-by-line, and examine all variables; allowing you to easily see exactly what's going on
* can simulate and run through the code in the actual environment

## Steps to xdebug, from scratch:
* install virtualbox
* install vagrant
* download homestead vagrant box 
```bash
# what you would normally do:
vagrant box add laravel/homestead

# to use a local file:
vagrant box add --name laravel/homestead /path/to/homestead-2.0-virtualbox.box
```

# Raw dump of scripts used by build cjdns daily builds repository for Ubuntu

## TODO:

 - [ ] Documentation
 - [ ] Update for 16.04 host system (migrate upstart to systemd, etc) 

## FAQ

 ### Why not a Launchpad PPA?
 
 Because cjdns git repository contains submodules, which makes it impossible to import into bzr. At the time it was easier to host a complete repo with full control over what's going on than to fetch code from git, preprocess it and upload it to Launchpad. It is an option that might be worth revisiting.
 

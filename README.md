# useful-links
A set of useful contents, such as tutorials, Q&amp;A, etc.

* Installing Loopback Stronloop on a Digital Ocean droplet: https://medium.com/@achintverma/installing-loopback-on-aws-digital-ocean-46070564f3a2#.rcazd8cwb
* Installing MySQL on Ubuntu: https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-14-04
* Remotely connecting to MySQL via ssh tunnel: https://www.digitalocean.com/community/questions/remotely-connecting-into-mysql-running-on-an-ubuntu-digital-ocean-node-with-jmeter-locally?answer=27096
https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-tunneling-on-a-vps
* Set up domain on Digital Ocean https://www.digitalocean.com/community/tutorials/how-to-set-up-a-host-name-with-digitalocean
https://www.digitalocean.com/community/tutorials/how-to-point-to-digitalocean-nameservers-from-common-domain-registrars
* Swap memory: http://samwize.com/2016/05/19/docker-error-returned-a-non-zero-code-137/

## Strongloop Loopback Framework
* Preparing for deployment: https://loopback.io/doc/en/lb2/Preparing-for-deployment.html

## Docker
* Installing on Ubuntu: https://docs.docker.com/engine/installation/linux/ubuntulinux/
* MySQL image: https://hub.docker.com/_/mysql/
* Building an image from a Dockerfile: https://docs.docker.com/engine/tutorials/dockerimages/#/building-an-image-from-a-dockerfile
* Image for Strongloop Loopback: https://hub.docker.com/r/allanoliveira/loopback/
* List stopped containers: docker ps --filter "status=exited"
* Remove stopped containers: docker rm $(docker ps --filter "status=exited" -q)
* Remove unused data: http://stackoverflow.com/questions/32723111/how-to-remove-old-and-unused-docker-images
* http://stackoverflow.com/questions/24272535/rebuild-container-after-each-change

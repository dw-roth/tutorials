# Buy a domain and host it on an Ubuntu cloud server

### In this tutorial you will 
#### Buy a domain name
#### Create a cloud-hosted Ubuntu server to host that domain
#### Configure DNS to map the domain name to the cloud-hosted server
#### Set up ssh to log into the server from the command line
#### Install Apache2 on the Ubuntu server
#### Configure Apache2 to host your domain
#### Put a bare-bones index.html on the server
#### Get and install an SSL certificate on the Ubuntu server

There are many options for buying domain names, configuring their DNS entries, and creating cloud-hosted servers. In this tutorial I use [DNSimple](https://www.dnsimple.com) to buy and manage 
the domain name, I will use [DigitalOcean](https://www.digitalocean.com) for the cloud Ubuntu server, and I will use [Let's Encrypt](https://letsencrypt.org) for the SSL certificate.
Digital Ocean makes it quite easy to get and install an SSL cert from Let's Encrypt on your server.

Assumptions: you have a rudimentary capability using a bash shell.

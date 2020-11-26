# Buy a domain and host it on an Ubuntu cloud server

### In this tutorial we will 
#### -[Buy a domain name](#buy-a-domain)
#### -[Create a cloud-hosted Ubuntu server to host that domain](#create-ubuntu-server)
#### -[Configure DNS to map the domain name to the cloud-hosted server](#configure-dns)
#### -[Set up ssh to log into the server from a bash shell](#setup-ssh)
#### -[Install Apache2 on the Ubuntu server](#install-apache2)
#### -[Configure Apache2 to host the domain we purchased](#configure-apache2)
#### -[Create a repository in github for our domain](#create-github-repository)
#### -[Create the bare-bones index.html file in our gihub repository](#create-html-file)
#### -[Clone the repository to our cloud server to that it is visible when someone goes to our domain in a browser](#clone-html-file-to-server)
#### -[Update our index.html file in github and then on the server](#update-html)
#### -[Get and install an SSL certificate on the Ubuntu server so that our site is secure (https)](#get-and-install-ssl-cert)

There are many options for buying domain names, configuring their DNS entries, and creating cloud-hosted servers. In this tutorial I use [DNSimple](https://www.dnsimple.com) to buy and manage 
the domain name, I use [DigitalOcean](https://www.digitalocean.com) for the cloud Ubuntu server, and I use [Let's Encrypt](https://letsencrypt.org) for the SSL certificate.

Assumptions: you have a rudimentary capability using a bash shell.

### Buy a Domain

I began using [DNSimple](https://www.dnsimple.com) several years ago as an easy way to manage my domains (map domain name to server, handle SSL certs, etc). Since DNSimple also allows me to buy domains, I've used it as my one-stop shop for buying and managing domains. You can purchase domains at other websites (e.g. bluehost.com) and manage your domains at other sites. You can even buy a domain at another site and transer it to DNSimple so that you can manage it through DNSimple. In this tutorial we will purchase and manage our new domain at DNSimple.

I assume that the ability to create an account on a website is a required skill to function in our society, so I will not walk you through the process. Note that DNSimple is not a free service. You can, however, choose a service with a 30-day free trial, though it requires a credit card to sign up. In the future I may add steps to do the same operations at a site that provides free services.

<img src="https://github.com/dw-roth/tutorials/blob/main/images/dnsimple_option_indiv_biz.png" width="500">

### Create Ubuntu Server

### Configure DNS

### Setup ssh

### Install Apache2

### Configure Apache2

### Create Github Repository

### Create HTML file

### Clone HTML file to server

### Update HTML

### Get and Install SSL cert



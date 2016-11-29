---
title: Nginx Basics For A Windows Guy
date: 2016-11-29 23:25:33.843000000 Z
---

## NGiNX Basics for a Windows Guy

#### File Locations
	/etc/nginx - default location


#### Commands
##### nginx control ([controlling nginx](http://nginx.org/en/docs/control.html))
	nginx -s stop
	nginx -s quit
	nginx -s reload
	nginx -s reopen

#### Get List of All Running NGINX Processes
	ps -ax | grep nginx


#### Handling Multiple Domains with NGINX
[Name-base virtual servers](http://nginx.org/en/docs/http/request_processing.html)


### Default (from droplet)



### Current DigitalOcean Setup
[see blog post](https://www.digitalocean.com/community/articles/how-to-serve-multiple-ghost-blogs-on-one-vps-using-nginx-server-blocks)

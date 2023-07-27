<!-- ABOUT THE PROJECT -->
## About The Project
**Network & Sys Admin**

&nbsp;
# **Introduction**
The Network & Sys Admin (NSA) project consists in the implementation of an online Gitlab.com server responsible for the CI and the CD, as well as 3 Debian servers (for MySQL, Frontend and Backend).
&nbsp;
## ©Project context**
With this server, you will be able to perform the following demonstration:
1. Prepare the infrastructure layer and configure the
machines with Ansible from a terminal
2. CI : Build, test and package your applications
on Gitlab
3. CD : Launch the deployment of each application
with Ansible, from Gitlab
4. Access each application.
&nbsp;

### Built With


* [![Gitlab][https://gitlab.com/]][Gitlab-url]
* [![ANSIBLE][https://docs.ansible.com/ansible/latest/getting_started/index.html]][Ansible-url]
* 💻 UTM
* 💻 Debian


### Prerequisites
### Setting up the gitlab server

* *Prerequisite:* Make sure ipv6 is disabled on your debian. [Method on debian 9](https://www.itzgeek.com/how-tos/linux/debian/how-to-disable-ipv6-on-debian-9-ubuntu-16-04.html#Method_1).
* Follow [this tutorial](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-gitlab-on-debian-9) to setup the server
* Create a self-signed [SSL certificate](https://support.ssl.com/Knowledgebase/Article/View/19/0/der-vs-crt-vs-cer-vs-pem-certificates-and-how-to-convert-them) and [install it](https://docs.gitlab.com/omnibus/settings/ssl.html#install-custom-public-certificates) (by putting it in the 
  * In `/etc/gitlab.gitlab.rb`: `external_url 'https://gitlab.devops.com'`
  * set `letsencrypt['enabled']` to `false`
  * I joined the certificate I was able to generate. It was not good enough for the runner integration, though :/
* Create a user and init the back and front repositories



## Table of contents
> * [Network & Sys Admin](#Network & Sys Admin)
>   * [Introduction](#introduction)
>   * [Project context](#project-context)
>   * [Built With](#BuiltWith)
>   * [Prerequisites](#Prerequisites)
> * [Members](#Members)
&nbsp;

<!-- CONTACT -->
## Members

* Damia Tobossi
* Wahab Dossou
* Nimrod Ladjouan
* Serge Gnansounou
* Stéphane Dossou

Project Link: [https://github.com/EpitechMscProPromo2024/T-NSA-700-COT_3](https://github.com/EpitechMscProPromo2024/T-NSA-700-COT_3)

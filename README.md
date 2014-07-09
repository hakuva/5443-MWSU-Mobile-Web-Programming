5443-MWSU-Mobile-Web-Programming
================================

Mobile web programming class
================================

Day 1:
================================

GitHub instructions.

creating servers.

ip address: 104.131.135.146

NAT - Network address transulation.

domain ex: mwsu.edu brings external ip address
sub domain ex: cs.mwsu.edu brings internal ip address

static ip addresses are unchanged ip addresses.
DHCP (Dynamic Host Control Protocol) brings up the new ip address it receives.

Servers must have static ip.

created server web-course2014 in digital ocean.

server commands
ls - listing
ll - long listing (ls -lah)

working directory cd /var/www/html

change permissions for the files

Owner   Group   Public
4 2 1   4 2 1   4 2 1
R W X   R W X   R W X

This file must have restricted access
chmod 700 info.php

www-data is apache server

ifconfig to get connected information

whoami is to get user info

uers - gives u user

adduser username


nano /etc/sudoers
is to edit sudoers.
go in this file and grant priviliges to the user u create


rm - remove files

rm -rf *

history - gives u all commands u type.

open notepad++ and connect it to your server


sudo chown -R  username:username folder name
get ownership of the folder

open index.htmlin notepad++ to edit it

<head> information about the page </head>
<body> contents of the page </body>

<!-- comment tag -->

<div> block level element divides the page</div> nothing prints out on same line

<span> tag spans over text

<span style="color:red"> adding a styling attribute of color red


span{
font-weight:bold;
color:green;
}

converts everything have span to following things

<ul> unordered list
<li> line item goes in <ul> or <ol>

<ol> ordered list


JSfiddle.net - lets u do HTML, CSS, Java Script and execute it

<img src="path to image"> to input an image

attributes in img tag

width
height

if only width is changed it changes with aspect ratio


<a href="any URL"> anchor tag to redirect to a URL specified

<p> paragraph tag this is also a block level tag

<h1-6> heading tags

<?php start php tag ?>
<h{$i}>


sudo apt-get install 


<table> shows data in tabular format</table>
<tr> table row
<td> Table columm or data
<th> table headings


padding space between inside of an element all over
margins - buffer the margins


Day 2:
================================

Text Wrangler is installation.

udacity.com is a online course website

<pre> is used so that white space or removed

<iframe src="url"> can bring other pages of html from another sources pages

associative arrays are introduced

take a snippet from bootsnipp.com

go to bootstrapcdn.com to get complete bootstrap

Day 3:
================================

GitHub instructions:
create a new folder and a file using touch file name


intialise git in folder
git init

git add -A to add all the files in the folder

git commit - m "your messsage"

git config --global user.name "hakuva"
to link github username to ur folder

it config --global user.email "sampatisai93@gmail.com"
to link github email to ur folder

git remote add origin git@github.com:hakuva/repository.git

git push -u origin master


git add -A
git commit -m "Adding my first file"
git config --global user.name "hakuva"
git commit -m "Adding my first file"
git config --global user.email "sampatisai93@gmail.com"
git config --global user.name "hakuva"
git commit -m "Adding my first file"
git status
git remote add origin git@github.com:hakuva/5443-MWSU-Mobile-Web-Programming.git
git push -u origin master
cd
cd ~/
ll
cd .ssh
ll
ssh-keygen
ll
cat id_rsa.pub
ssh-keygen -T rsa -C sampatisai93@gmail.com
ssh-keygen -t rsa -C sampatisai93@gmail.com
cat id_rsa.pub



copy rsa key

go to your folde type ssh -T git@github.com

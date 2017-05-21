# A deployable Platform-As-A-Service for Yocto Project

## Introduction

The goal of this project is to create a deployable PaaS(Platform-As-A-Service) framework for everyone and anyone to enable into their machine/server a fully useable web service for Yocto Project.

In order to achieve this, we are leveraging on a few technologies over at Yocto Project but not limited to them. Currently we are making use of Toaster but we are also considering Autobuilder as the web GUI to enable users to easily "develop" their own Linux distros without having to use too much CLI (Command Line Interface). Web SSH is still available to those that prefers more control over their builds.

## What is Yocto Project?

tl;dr 
It is a tool that helps to build your own Linux distributions via a set of configurations that the user set. The output of this tool is a Linux image.

## Deployment

*Have yet to update but I'll give a short overview.

*The deployment of this framework should be as simple as an installer running directly on your machine/server and the output would be two websites. First website is the admin website, whereby the admin is able to view status of the machine and control the builds and users entering the machine to use for building their own Linux distro. Second website is the users website, users would have their own admin page whereby they are able to control their different builds and access Toaster/Autobuilder from there.

## Developers & Contributors

Stanley Phoong
Rebecca Chang
Wei Tee, Ng
Libby
Chin Huat, Ang

---
title: "Cubic Custom OS Maker"
date: 2024-03-09T18:54:49+01:00
draft: true
---

## Introduction

Cubic (Custom Ubuntu ISO Creator) is a GUI wizard to create a customized Live ISO image for Ubuntu and Debian based distributions.

Cubic permits effortless navigation through the ISO customization steps and features an integrated virtual command line environment to customize the Linux file system. You can create new customization projects or modify existing projects. Important parameters are dynamically populated with intelligent defaults to simplify the customization process.

## Installation

Cubic runs on distributions based on Ubuntu 18.04.5 Bionic and above.

```bash
sudo apt-add-repository universe
sudo apt-add-repository ppa:cubic-wizard/release
sudo apt update
sudo apt install --no-install-recommends cubic
```

## Usage

First we need to open or create a Cubit project:

![Cubit Start Page](/static/images/cubic-start-page.png)

If no project exists, one can be created by clicking on the folder icon

Then we can fill the information about the custom OS on the metadata page

![Cubic Metadata Page](/static/images/cubic-metadata-page.png)

Lastly we can customize the OS with the terminal page

![Cubic Terminal Page](/static/images/cubic-terminal-page.png)

Here is an example installing htop:

![Cubic Installation Htop](/static/images/cubic-terminal-page-install.png)

After customizing the image with the terminal, it is possible to not include some programs in the standard installation as well as creating a minimal install.

![Cubic Versions Page](/static/images/cubic-versions-page.png)

Last steps are selecting kernel and compression method

![Cubic Kernel Page](/static/images/cubic-kernel-page.png)

![Cubic Compression Page](/static/images/cubic-compression-page.png)

After generating the image you can review important information on the finish page

![Cubic Finish page](/static/images/cubic-finish-page.png)

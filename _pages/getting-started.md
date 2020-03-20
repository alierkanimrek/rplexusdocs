---
layout: page
title: Getting started with Rplexus.net
permalink: /getting-started/
---

### Overview
Rplexus is based on a very simple philosophy. You can create your client easy 5 steps below.

Rplexus is a central server between devices. In Rplexus terminology, each client is called Node and they connect to the server with a small application. So multiple client software can run on one device.

**Node = Client**

Each Node and its data are defined by the user from the rplexus.net web interface. In Rplexus terminology, each data is called Task and carries data such as variable_name = "value". You can write the your own codes or use the libraries developed by the community for getting data from sensors.

**Task = Variable Name**

The Rplexus server redirects data from clients to the user's web interface and other shared clients. With shared node tasks you can establish a network.

You can configure this network to set up your smart home system and manage your network from any web browser.

### Step 1) Sign up rplexus.net
You can create an account on [https://rplexus.net/user/signup](https://rplexus.net/user/signup){:target="_blank"}

### Step 2) Create your first Node
You will see "Create Node" section when you login, just write your new node name and create one. [https://rplexus.net/user/login](https://rplexus.net/user/login){:target="_blank"}

### Step 3) Client Installation
Client application is simple Python script and tested only Linux systems for now. [https://github.com/alierkanimrek/rpct](https://github.com/alierkanimrek/rpct){:target="_blank"}

You have two options for download on command line;
```bash
wget https://github.com/alierkanimrek/rpct/archive/master.zip
unzip master.zip
```
or
```bash
git clone https://github.com/alierkanimrek/rpct.git
```
#### Requirements
Client application needs **Python version 3** and **Tornado library version 6**. 

You can check Python version.
```bash
python3 -V
```
Then install Tornado lib.
```bash
pip3 install tornado
```

### Step 4) Client Configuration

### Step 5) Create your first View

### Advanced topics

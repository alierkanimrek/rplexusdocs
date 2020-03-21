---
layout: page
title: Client Axones
permalink: /axones/
---

## NixSys
OS:`Linux` Requirements:`None` 

System Information

**Parameters**
* **name**: string
* **release**: string
* **version**: string
* **machine**: string
* **arch**: array
* **cpu_model**: string
* **cpu_processor**: string
* **cpu_mhz**: string
* **mem_total**: string
* **mem_free**: string
* **cpu_usage**: string

**Methods**
* **__init__()**
* **update()**:
> Update cpu and ram values.


## NixCat
OS:`Linux` Requirements:`None`

Txt file dump.

* **file**: string
* **row**: int
* **raw**: binary
* **utf8**: string
* **html**: string

**Methods**
* **__init__(file:str="", row:int=10)**
* **update(file:str="", row:int=-1)**
> Update file content. You can change file and row parameters while updating. These parameters will be permanent.

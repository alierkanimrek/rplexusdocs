---
layout: page
title: Client Axones
permalink: /axones/
---

## NixSys
OS:`Linux` Requirements:`None` 

System Information

**Parameters**

|Name|Type|Description|
|---|---|---|
|**name**|string
|**release**|string
|**version**|string
|**machine**|string
|**arch**|array
|**cpu_model**|string
|**cpu_processor**|string
|**cpu_mhz**|string
|**mem_total**|string
|**mem_free**|string
|**cpu_usage**|string

**Methods**

|Name|Parameters |Return |Description|
|---|---|---|---|
|**__init__**|()|
|**update**|()|None|Update cpu and ram values.


## NixCat
OS:`Linux` Requirements:`None`

Txt file dump.

**Parameters**

|Name|Type|Description|
|---|---|---|
|**file**|string| File name with full path, /var/log/syslog for example.
|**row**|int| How many lines will be read from the end. Highest value can be slow.
|**raw**|binary| Content binary format.
|**utf8**|string| UTF-8 decoded string.
|**html**|string| Add </br> for every line ends.

**Methods**

|Name|Parameters |Return |Description|
|---|---|---|---|
|**__init__**|(file:str="",row:int=10)|None|
|**update**|(file:str="",row:int=-1)|None| Reads file. You can change filename and row parameters while updating. These parameters will be permanent.

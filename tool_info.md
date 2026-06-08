---
layout: default
title: Julian's DESR tool information
permalink: /tool_info/
---

# Introduction

This page contains a list of Julian's tools for DESR/PSX DVR systems.  
This page is still a work in progress, so minimal information and instructions are contained on this page.  

## Help and support

If assistance is required regarding the tools or information specified on this page, please join the Phenom Mod discord channel as linked at https://store.phenommod.com  

## Tools

### HDD rework 7zip

* Binary: https://github.com/uyjulian/helloWorldPS2/releases/download/v0.0.1-rchddreworktest1/helloWorldPS2-v0.0.1-rchddreworktest1.zip
* Source: https://github.com/uyjulian/helloWorldPS2/tree/v0.0.1-rchddreworktest1

Note: finishes in around 2.3 minutes in emulator with 1.31\_LITE  
Repack as follows:  
```bash
7z x -ox 211_for_repart.7z
7z a -mx=3 HDDREWK.7Z ./x/JOBS.DAT
7z a -mx=3 HDDREWK.7Z ./x/* '-xr!JOBS.DAT'
```

### HTTP server for DVR partition contents

* Binary: https://github.com/uyjulian/helloWorldPS2/releases/download/v0.0.1-mongoosetest1/helloWorldPS2-v0.0.1-mongoosetest1.zip
* Source: https://github.com/uyjulian/helloWorldPS2/tree/v0.0.1-mongoosetest1

Note: around 3 MB/s speed  

[Go to the top of the page](#)  
[Return to top page](..)  

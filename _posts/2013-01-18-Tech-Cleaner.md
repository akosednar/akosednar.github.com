---
layout: post
title: "Tech Cleaner"
categories: [blog, projects]
---

One of the main greuling parts of working with Windows business and home computer users is when you need to clean up their computer. However, this can be very time consuming. As a result, I wrote a little script in Autoit (a quick and easy scripting language) to do most of the work for me. 

Here's an overview of what it does:

* Creates some directories to run (and creates a log file) 
* Kills Non-Whitelisted Processes 
* Checks Servces 
* Backups Registry 
* Checks Registry 
* Kills any Proxies 
* Downloads ComboFix, Rkill, Tdskiller, CCleaner, Defraggler, Unlocker, Revouninstaller
* Installs Microsoft Essentials, and updates it 
* Runs Rkill 
* Runs TSKiller 
* Runs ComboFix 
* Runs CCleaner 
* Runs Defraggler

You can find the code for the script in its repo on github at [https://github.com/akosednar/TechCleaner](https://github.com/akosednar/TechCleaner).

Please note, this software is licensed under [Creative Commons Attribution-NonCommercial 3.0](http://creativecommons.org/licenses/by-nc/3.0/). It is free to use and edit for personal, and non-profit projects but you will need to contact me for permission to use this commcerially. 

Also note, it requires the following to compile:

* [CompInfo.au3](http://www.autoitscript.com/forum/topic/29404-computer-info-udfs/) by *JSThePatriot*
* [Zip.au3](http://www.autoitscript.com/forum/topic/73425-zipau3-udf-in-pure-autoit/) by *torels_* 
* [WinHttp.au3](https://code.google.com/p/autoit-winhttp/) by *trancexx, ProgAndy*


At the moment, I plan on rewritting much of the script. I also plan on adding features to account for a combofix reboot, deploy logmein rescue, and more.

If you have any comments or feature requests, or just want to contribute to the code check out the Git repo and submit an issue or pull request.
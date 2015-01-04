Micro-puppet
============

A DSL around tiny-puppet for the keystroke impaired.

Why
----
We need more beerops time. And because 2015 is the year of DSLs.

Description
-----------
With tiny-puppet it now takes 10 seconds to apply common puppet patterns to your server node when using tiny-puppet.  But personally we can do better. I wanted something even shorter and less verbose.  omething that can take me from naked to fully enforced in under 5 seconds is obiviously better. Enter micro-puppet.  I cannot afford to spare 5 seconds.  A DSL around the already shortened tiny-puppet DSL just makes sense.  Its a triple DSL threat and great things always come in threes.  

Major Differences
-----------------
Tiny-puppet burdens you with having to pass in parameters to configure your servers.  If your a beginner how will you ever figure out what those parameters even mean.  With micro puppet you no longer need to pass in those pesky parameters.  Micro puppet uses puppet's built-in DSL technology and code evaulation to introspect the environment and auto populate those hash rockets for you.  Its like magic!  But we call it syntactic sugar.  

Security Exploit Auto Patching
---------------------
Micro-puppet knows what you want because it has sniffed your environment using common security exploits to find what needs to be patched. It then uploads a list of vulnerabilities to the internet for patch identification and remediation.  Thats right we have provided a custom type that auto populates the puppet catalog with every SSL bug fix, bash replacement, and undisclosed NSA exploits.  We call this Fort-Knox. 

Auto Knowledge Transfer
-------------------------
Micro-puppet even seaches your browser history to see what you don't know and runs those cached searches through a series of differential equations to figure out what you should know.  Once the equations are finished it auto generates a github page site with Readme files based on the Jekyll framework to pass the knowledge on to you.  Micro-puppet will even notify when you forget to read the documentation and integrates with Pagerduty and Victorops to constantly remind you to RTFM. 

Requirements
------------
Works with Puppet 2, 3, and upcoming 4

Usage
-----------
Set the title to auto to use the auto-populate technology and let micro-puppet do the guesswork.
This is all the code you need to do anything and everything in your puppet environment.  Its that easy.  Four lines of code and your done.

Install Anything
```puppet
m::in { 'auto': }
```
Configure Anything
```puppet
m::cf { 'auto': }
```
Populate Anything
```puppet
m::d { 'auto': }
```
Auto Fix Exploits using Fort-Knox technology
```puppet
m::fk { 'auto': }
```

Installation Procedure
----------------------
Actually micro-puppet is now installed.  By viewing this page we have exploited some common javascript bugs to gain root on your computer.  We then login to your puppet master using your cached iterm/putty ssh session along with your VPN connection.  So sit back and relax and watch the reports roll in.  Your job is complete my friend.

Micro-puppet
============

A DSL around tiny-puppet for the keystroke impaired.

Why
----
We need more beerops time. And because 2015 is the year of DSLs.

Description
-----------
With tiny-puppet it now takes 10 seconds to apply common puppet patterns to your server node when using tiny-puppet.  But personally, I think we can do better. I wanted something even shorter and less verbose.  Something that can take me from naked to fully enforced in under 5 seconds is obiviously better. Enter micro-puppet.  I cannot afford to spare 5 seconds.  A DSL around the already shortened tiny-puppet DSL just makes sense.  It's a triple DSL threat and great things always come in threes.  

Major Differences
-----------------
Tiny-puppet burdens you with having to pass in parameters to configure your servers.  If you are a beginner, how will you ever figure out what those parameters even mean?  With micro puppet you no longer need to pass in those pesky parameters.  Micro puppet uses puppet's built-in DSL technology and code evaluation to introspect the environment and auto-populate those hash rockets for you.  It's like magic!  But we call it syntactic sugar.  

Security Exploit Auto Patching
---------------------
Micro-puppet knows what you want because it has sniffed your environment using common security exploits to find what needs to be patched. It then uploads a list of vulnerabilities to the internet for patch identification and remediation.  That's right. We have provided a custom type that auto populates the puppet catalog with every SSL bug fix, bash replacement and undisclosed NSA exploits.  We call this Fort Knox. 

Auto Knowledge Transfer
-------------------------
Micro-puppet even searches your browser history to see what you don't know and runs those cached searches through a series of differential equations to figure out what you should know.  Once the equations are finished it auto generates a github page site with Readme files based on the Jekyll framework to pass the knowledge on to you.  Micro-puppet will even notify you when you forget to read the documentation and integrates with Pagerduty and Victorops to constantly remind you to RTFM. 

Requirements
------------
Works with Puppet 2, 3, and upcoming 4

Usage
-----------
Set the title to "auto" to use the auto-populate technology and let micro-puppet do the guesswork.
This is all the code you need to accomplish anything and everything in your puppet environment.  It's that easy.  Four lines of code and you're done.

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

Where is the code?
-----------------------
You might be asking yourself where is the actual code?  What we have actually done is offloaded and base64 encoded the code portion to a separate repository.  We then fragmented the code across a P2P network.  During the installation process we downloaded a lightweight nodejs P2P client and then install the micro-puppet module.  Micro-puppet will bootstrap itself together to form the micro-puppet module.  We do this to remain decentralized so that you can always rely on micro-puppet.  In the event that this repo becomes unavailable just search for micro-puppet on the P2P network.  This is true 100% uptime, not that 99.999999999999% bullshit.

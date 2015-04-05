Micro-puppet
============

A DSL around tiny-puppet for the keystroke impaired.

Why
----
We need more beerops time. And because 2015 is the year of DSLs.

Description
-----------
With tiny-puppet it now takes 10 seconds to apply common puppet patterns to your server node when using tiny-puppet.
But personally, I think we can do better. I wanted something even shorter and less verbose.
Something that can take me from naked to fully enforced in under 5 seconds, which is obviously better. Enter micro-puppet.
A DSL around the already shortened tiny-puppet DSL.  It's a triple DSL threat and you know great things always come in threes (Puppet --> Tiny-Puppet --> Micro-Puppet).

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

Depreciation Remediation (a.k.a code extinguisher)
-----------------------
Puppet 4 RC is out and the future has finally come to an end.  Its time to put the latest release into production.  But wait, your puppet code was written in the 2.7.x era and now nothing works against the new parser.  So what can you do?  Micro-puppet to the rescue.  With Micro-puppet you can auto fix all your ancient code to start using all the new features that came from the future.  Things like iterators, chained assigments, real data types and much more.  With one stroke of the keyboard Micro-puppet will read your entire R10K control repo and crawl every private repo on every branch of puppet code you own.  Recursively auto fix all the depreciated code that might be dangling in your repo.  More importantly, Micro puppet can do all this in only 100 lines of code.  Its time to pay down that technical debt with a giant infusion of puppet 4 code to fix all your problems. So say goodbye to Ruby 1.8.7 and say hello to the future. 

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

Do everything at once
```puppet
   generate_beerops('auto')      # a puppet function that uses create_resources to run all of the manifests above.

```

Auto Fix deprecated code (a.k.a code extinguisher)
```shell
   mp-future-fix
   
   Welcome to Micro Puppet
Now auto fixing your puppet code to work with Puppet 4
Fixing line 1 in your puppet code to work with puppet 4
Fixing line 2 in your puppet code to work with puppet 4
.
.
.
Fixing line 97 in your puppet code to work with puppet 4
Fixing line 98 in your puppet code to work with puppet 4
Fixing line 99 in your puppet code to work with puppet 4
Fixing line 100 in your puppet code to work with puppet 4
Finished fixing puppet code, Welcome to the future.
```


Installation Procedure
----------------------
Actually micro-puppet is now installed.  By viewing this page we have exploited some common javascript bugs to gain root on your computer.  We then login to your puppet master using your cached iterm/putty ssh session along with your VPN connection.  So sit back and relax and watch the reports roll in.  Your job is complete my friend.

Where is the code?
-----------------------
You might be asking yourself "Where is the actual code?"  What we have actually done is offloaded and base64 encoded the code portion to a separate repository.  We then fragmented the code across a P2P network.  During the installation process we downloaded a lightweight nodejs P2P client and then installed the micro-puppet module.  Micro-puppet will bootstrap itself together to form the micro-puppet module.  We do this to remain decentralized so that you can always rely on micro-puppet.  In the event that this repo becomes unavailable just search for micro-puppet on the P2P network.  This is true 100% uptime, not that 99.999999999999% bullshit.

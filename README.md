What is this?
=============

These are a collection of scripts that make my life a little bit easier every
day. Most of them are meant to be run on linux, but they should work in any
environment close to unix.

gitignore
---------

Generates a gitignore file from http://gitignore.io

Usage:

	gitignore vim,intellij,linux >> .gitignore

openport
--------

Opens a port in my iptables setup. This script assumes that iptables is
configured similarly to mine. In my case, I have a TCP and a UDP chain. The
script adds entries in those chains.

Usage:

	sudo openport <port>

actr
----

Starts up the actr environment with the gui on linux. This script assumes that
you have clozure commons lisp installed and that actr in installed under 
`~/opt/actr6`.


#Banyan: A Forth Package System

A modern language is only as good as its package management system.

This isn't a first priority, but it should be integrated with the runtime distribution as soon as possible.

I'd argue that the sensible thing to do is survey existing package management systems for languages, and simply fork one. The less support code we have to maintain, the better, and there's no special reason that the Ficus package system should be written in Forth. 

The actual loading and use of packages will be part of the core runtime: fetching, resolving and installing the packages can be offloaded to an existing system. 

---
layout: page
title: "Dependency Explorer"
date: 2013-09-19 17:45
categories:
navbar: depexp
---

<div class="pull-right screenshot-right"><a href="/images/depexp-screenshot-1.png"><img src="/images/depexp-screenshot-1-preview.png" class="img-responsive img-thumbnail" alt="Dependency Explorer"></a></div>

This tool is intended to help developers of enterprise level applications to track down whole tree of dependencies between examined assembly and all other libraries that it needs to be able to function. This tree can be quite complicated especially in case if application suite consists of multiple solutions.

Current features:

- assembly dependency analysis via references

Planned features:

- analyze of DI for MEF – to help understand what assembly needs, and which assemblies can provide implementation of those needs
more detailed info on dependency link between two assemblies (exact types of assembly B used by examined assembly A)
- visualization of all assemblies’ dependencies in a given folder

Prerequisite to run:

- at least Windows 7 with .NET 4.5 installed

If you are not sure if the tool is useful for you, then you can try it for free and decide if that is what you need.

Missing a feature? Let us know what this tool needs to have!

- [Download](http://media.softin.co/DependencyExplorer-v1.0.0.35.zip)
- [Buy a license](http://sites.fastspring.com/softtiny/product/dependencyexplorer)

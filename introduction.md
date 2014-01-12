---
layout: top-level
title: Introduction
prev: '<a href="preface.html">Prev: Preface</a>'
next: '<a href="why-ansible.html">Next: Why Ansible?</a>'
---

# Introduction

This is a book on getting started with Ansible, an open-source software provisioning tool that is starting to find an audience amongst developers who also do some sysadmin work.  (Plenty of sysadmins are adopting it too).

It complements the official documentation written by the great folks over at AnsibleWorks.

## Who Is This Book For?

I've written this book primarily for developers who currently do some sysadmin work too, and who are looking to use Ansible to start automating provisioning and deployments.  If you're a full-time sysadmin who is new to Ansible, you'll also get a lot out of this book.

You will need to be comfortable doing basic Linux administration from the command-line.  Most of the examples are for Ubuntu 13.10.

## What Will You Learn From This Book?

This book will teach you the key skills you need to use Ansible:

* the [key concepts](key-concepts.html) behind how Ansible works, and where to find more information about them in the official Ansible documentation.
* how to [install Ansible](installing-ansible.html) and how to [prepare a computer to be provisioned by Ansible](preparing-a-computer.html)
* how to [create your first playbook](first-playbook.html) and how to [organise your Ansible playbooks](organising-your-ansible-files.html)
* how to [build an Ansible role](building-roles.html) by following a simple three-point plan
* how to [build and install config files](working-with-config-files.html)
* how to [restart services when your role makes changes](restarting-services.html)
* how to [add dependencies to your Ansible roles](adding-dependencies-to-roles.html)
* how to [make your Ansible roles repeatable](making-roles-repeatable.html) so that you can safely run them time and time again against the same computer
* how to [debug and troubleshoot roles](debugging-failing-roles.html) when they stop working or aren't working first time around
* how to install software that needs [building from source](building-software-from-source.html), and how to use [temporary install scripts](temporary-install-scripts.html) when all else fails
* how to use [meta-roles](using-meta-roles.html) to simplify your playbooks as complexity grows
* how to [support multiple operating systems](multiple-operating-systems.html) from the same, single Ansible repo
* how to [manage the Ansible inventory](managing-the-inventory.html) as you start to use Ansible on more computers

The book finishes with a collection of [miscellaneous tips](miscellaneous-tips.html) that will save you time and trouble as you use Ansible further.

## Why Learn From Me?

I've been using Ansible daily since November 2012 in my day job at DataSift, where I use it to build dev and test environments large and small.  I've had fourteen months to make lots of mistakes and figure out which approaches stand the test of time, and why they work.  I've put the results into this book for you.

I've been building and managing UNIX and Linux servers connected to the Internet for 20 years.

As a developer, I've been speaking at conferences and running tutorial workshops since 2004.  I am a co-author of the Zend Certification Study Guide for PHP 4, and was one of the early contributors to [php|architect](http://www.phparch.com) magazine.  I've been contributing to and creating open-source software for 20 years, most recently [Hubflow](http://datasift.github.io/gitflow/) and [Storyplayer](http://datasift.github.io/storyplayer).

You can learn more about me at [www.stuartherbert.com](http://www.stuartherbert.com).
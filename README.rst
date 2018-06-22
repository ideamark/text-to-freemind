Text-to-Freemind
================

A simple text to freemind conversion program


Overview
========

This program converts tab-indented UTF-8 text files into an XML format suitable
for display by Freemind. It was written out of annoyance with the Freemind user
interface, and the lack of 'merging' capabilities when collaborating with other
people.

Author: Mark Young <ideamark@qq.com>
The origin author is Wouter Bolsterlee <uws@xs4all.nl>. Thanks for sharing.

It is a new version of text-to-freemind by some modification.

This program is distributed under the GPL v2 (or later) license.


Usage
=====

To convert a single text file into a Freemind file, use::

    $ text-to-freemind input-file.txt

You can use it as a filter (using shell pipes) as well::

    $ cat some-text-data.txt | text-to-freemind


Requirements
============

The conversion program is written in Python (tested with 2.4 and 2.5) and
requires an ElementTree implementation. Install python-elementtree or
python-celementtree (included in Python 2.5) if you run into programs.


Issues, problems, and feedback
==============================

This program is a quick hack, so don't expect too much of it. If you feel like
contacting me with problems or suggestions, please mail me. Thanks.


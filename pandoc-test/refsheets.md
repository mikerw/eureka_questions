[![UNC](/assets/img/161icon.png)](/) [Tools for Information Literacy](/)
[Syllabus](/syllabus/) [Schedule](/schedule/)
[Assignments](/assignments/) [Reference](/refsheets/)

Reference
=========

Operating systems and tools
===========================

UNIX
----

⊕**UNIX** is a general purpose operating system originally developed in
the 1970s by Ken Thompson and Dennis Ritchie at Bell Labs. Its utility
and wide use has given rise to a number of clones—operating systems that
are functionally identical.

[FOSSWire UNIX Command
Reference](https://ubuntudanmark.dk/filer/fwunixref.pdf)

Linux
-----

⊕**Linux** is one such UNIX clone originally invented in 1991 by Linus
Torvalds. It is now among the most widely used operating systems in the
world. If you have used the Internet, you have interacted with Linux
perhaps without even realizing it. Your CodeAnywhere containers run
Linux.

[](The%20Linux%20Command%20Line%20-%20William%20E.%20Shotts,%20Jr.)[http://linuxcommand.org/tlcl.php](http://linuxcommand.org/tlcl.php)

[The Ultimate Linux Newbie
Guide](http://linuxnewbieguide.org/?page_id=5)

Bash (UNIX shell) {#bash-(unix-shell)}
-----------------

⊕**Bash** is the name of the shell and command language that we use most
frequently in Linux and other UNIX clones. It is a text-interface
command line envrionment but it can also read commands from files in the
form of scripts.

[](Learning%20the%20shell%20-%20William%20E.%20Shotts,%20Jr.)[http://linuxcommand.org/lc3\_learning\_the\_shell.php](http://linuxcommand.org/lc3_learning_the_shell.php)

[](Writing%20shell%20scripts%20-%20William%20E.%20Shotts,%20Jr.)[http://linuxcommand.org/lc3\_writing\_shell\_scripts.php](http://linuxcommand.org/lc3_writing_shell_scripts.php)

### Reference sheets from in-class activities

These reference sheets correspond to things that we actualy did or will
do in class (depending on how fast I can aggregate them and get them
posted here).

[Remote operation](/refsheets/remote-ref/)

[Networking](/refsheets/network-ref/)

VIM (UNIX text editor) {#vim-(unix-text-editor)}
----------------------

⊕**VIM** is a text-only, command-based text editor that is meant to be
used when no graphical user environment is available. When making
commits in git, if you forget to add a message in the command, this is
the editor that pops up automatically. It is good to know this and other
text editors just in case you are using a Linux system that only has a
command line interface.

[VIM Cheat Sheet - Richard Torruellas](http://vim.rtorr.com/)

[VIM Quick Reference Card - Laurent
Gregoire](http://tnerual.eriogerg.free.fr/vimqrc.pdf)

Version Control
===============

Git
---

⊕**git** is a distributed version control system that keeps track of the
changes between plaintext source files. It can be used for collaboration
or for managing and keeping track of workflows for individuals. While
primarily intended for software source code, git works with any
plaintext files, and so can also be used for authoring of other kinds.

[Git - The Simple Guide
(PDF)](http://rogerdudler.github.io/git-guide/files/git_cheat_sheet.pdf)
[(WEB)](https://rogerdudler.github.io/git-guide/)

[Git Cheat Sheet -
GitHub](https://education.github.com/git-cheat-sheet-education.pdf)

[Git Tutorials and Training -
Atlassian](https://www.atlassian.com/git/tutorials/)

Reference sheets from in-class activities {#reference-sheets-from-in-class-activities}
-----------------------------------------

[Git local](/refsheets/git-ref/)

GitHub
------

⊕**GitHub** is a platform that allows for users to keep copies of their
open source, plaintext repositories online, in a single centralized
location. It also adds a social interaction layer to the process of
managing version-controlled source files.

[Hello World - GitHub
Guides](https://guides.github.com/activities/hello-world/)

### Reference sheets from in-class activities {#reference-sheets-from-in-class-activities}

[Git remote](/refsheets/github-ref/)

Markup languages and web code
=============================

Markdown
--------

⊕**Markdown** is a simple, human-readable, free markup syntax for
rendering plaintext source files into HTML or other formats when run
through an interpreter.

[Markdown Cheat Sheet -
Packetlife.net](http://packetlife.net/media/library/16/Markdown.pdf)

[Makdown: The Ins and Outs - Dan
Harper](http://code.tutsplus.com/tutorials/markdown-the-ins-and-outs--net-25482)

HTML5
-----

⊕**HTML** is an acronym for "HyperText Markup Language." "Hypertext" is
text that contains links to other text. The Web, as we know it, relies
on hypertext to for us to communicate with systems and with other
humans. It is the medium of Web content.

[HTML5 Cheat Sheet -
WebsiteSetup.org](http://websitesetup.org/HTML5-cheat-sheet.pdf)

[W3CSchools HTML(5) Tutorial](http://www.w3schools.com/html/default.asp)

CSS3
----

⊕**CSS** is an acronym for "Cascading Style Sheet." If HTML is the
medium for web content, then CSS is the palette for the visual styling
of the web. Whenever a website looks like anything other than just a
blank page, there is CSS involved.

[CSS3 Cheat Sheet - Leslie
Franke](http://lesliefranke.com/sandbox/ref/csscheatsheet.pdf)

[W3CSchools CSS Tutorial](http://www.w3schools.com/css/default.asp)

Jekyll and Liquid
-----------------

⊕**Jekyll** is a blog-aware static site generator. It uses raw text
files in place of a database to store content, which it parses and
renders into web code.

[Jekyll Cheatsheet - Rico Sta.
Cruz](http://ricostacruz.com/cheatsheets/jekyll.html)

⊕**Liquid** is a templating engine with simple markup used by Jekyll to
render dynamic elements of a site.

[Liquid for Designers - Shopify Dev
Team](https://github.com/Shopify/liquid/wiki/liquid-for-designers)

[Liquid for Programmers - Shopify Dev
Team](https://github.com/Shopify/liquid/wiki/Liquid-for-Programmers)

Document processing
===================

Pandoc
------

⊕**Pandoc** is a universal document converter invented and developed by
John MacFarlane. It is an indispensible tool for converting to and from
a multitude of text document formats.

A good set of commands and rationale for using Pandoc to create and
convert documents lives here:

[getting off the word standard: your academic life in plain text - Pavel
Iosad](http://anghyflawn.github.io/teaching/2015/ilw-pandoc/)

The help/manpage file for Pandoc is linked here: [Pandoc User
Guide](http://pandoc.org/README.html). Use it!

### Reference sheets from in-class activities {#reference-sheets-from-in-class-activities}

[Pandoc](/refsheets/pandoc-ref/)

Databases
=========

MySQL
-----

⊕**MySQL** is an open source relational database management system
(RDBMS) that uses structured query language (SQL) syntax. It was
invented by Michael Widenius and David Axmark in the mid 1990s. It is
now among the most widely-used database systems in the world. It ships
with only a command line interface (CLI) and can be scripted.

[SQL Tutorial - W3Schools](http://www.w3schools.com/sql/)

[MySQL 5.5 Reference Manual - MySQL -
ORACLE](https://dev.mysql.com/doc/refman/5.5/en/)

Presentations
=============

Reveal.js
=========

⊕**Reveal.js** is an open source presentation framework for HTML5
invented by Hakim El Hattab. It allows content creators to develop
slideshows as simply as they would web pages. It also has the capacity
to add audio narration using a plugin.

### Reveal example presentations

[Reveal.js: The HTML5 Presentation Framework - Hakim El
Hattab](http://lab.hakim.se/reveal-js/#/)

[Example presentations -
Reveal.js](https://github.com/hakimel/reveal.js/wiki/Example-Presentations)

### Reveal tutorials

[Reveal.js Tutorial-Reveal.js for Beginners - Tom
Campbell](http://htmlcheats.com/reveal-js/reveal-js-tutorial-reveal-js-for-beginners/)

Productivity suites
===================

LibreOffice
-----------

[LibreOffice Documentation for all
Packages](https://www.libreoffice.org/get-help/documentation/)

All the things
==============

Web developer Rico Sta. Cruz has published all of his own cheatsheets on
his website. They are all quite excellent and can serve as a useful
reference for anyone just starting out in tech. Check them out.

[Cheatsheets - Rico Sta. Cruz](http://ricostacruz.com/cheatsheets/)

Reference -

* * * * *

-   [ John D. Martin III](http://johndmart.in "Instructor home page")
-   [ john.d.martin.iii@unc.edu](mailto:john.d.martin.iii@unc.edu "Email instructor")
-    11:30-13:00
-    MoTuWeThFr
-    117 Manning Hall
-   [](https://sakai.unc.edu/portal/site/inls161s216 "UNC Sakai site for this course")
-   [](https://github.com/inls161 "GitHub organization for this course")
-   [](https://inls161.slack.com "Join the Slack conversations for this course")
-   [](/feed "Add RSS feed")

TOOLS FOR INFORMATION LITERACY   |   INLS161-001 (Summer II) \
 Tools and concepts for information literacy. Includes software use and
maintenance, computer applications, and networked information systems. \
\
 [![Creative Commons
License](http://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/deed.en_US)
This work is licensed under a [Creative Commons
Attribution-NonCommercial-ShareAlike 4.0 Unported
License](http://creativecommons.org/licenses/by-nc-sa/4.0/deed.en_US). \
 [Content © 2016 John D. Martin III](/credits/)

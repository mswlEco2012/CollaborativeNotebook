CollaborativeNotebook
======================

Introduction
=============

Collaborative Notebook for Economic Aspects Subject coursed in [Master on Libre Software (Master Universitario en Software libre](http://master.libresoft.es/) at [Universidad Rey juan Carlos](http://www.urjc.es/).

Goals
======

The goal of this project is to to create a ``collaborative notebook`` with the working class notes from students.

Requirements
=============

1. LaTeX: LaTeX is a high-quality typesetting system.
2. git: Distributed version control system.

Note:

    This document is only for Linux environments.

Install Git
-------------

Using your preferred package manager of your Linux distribution.

*   Debian/Ubuntu:

        $ apt-get install git

*   Fedora:

        $ yum install git

*   Gentoo:

        $ emerge --ask --verbose dev-vcs/git

*   Arch Linux:

        $ pacman -S git

*   FreeBSD:

        $ cd /usr/ports/devel/git
        $ make install

*   Solaris 11 Express:

        $ pkg install developer/versioning/git

*   OpenBSD:

        $ pkg_add git

Install LaTeX
--------------

Here is the installation process using Ubuntu. In other Linux distributions you have to use your distro package manager.

How to install LaTeX in Ubuntu:

        $ sudo apt-get install texlive

The above command will install a basic subset of TeX Live’s functionality. To install all the packages in the LaTeX distribution, you have to run the following command:

        $ sudo apt-get install texlive-full

Files Description
==================

Images Directory
------------------

Place the images in this directory:

        ├── img
            ├── by.png
            └── by-sa.png

Bibliography
-------------

Bibliography file to update with Lesson references:

        ├── MSWL_ECO.bib

Documentation files
--------------------

Main LaTeX file from which all lesson files are linked:

        ├── MSWL_ECO_main.tex

Each file per Lesson:

        ├── MSWL_ECO_lesson1.tex
        ├── MSWL_ECO_lesson2.tex
        ├── MSWL_ECO_lesson3.tex
        ├── MSWL_ECO_lesson4.tex
        ├── MSWL_ECO_lesson5.tex

Description project file:

        ├── README.md

Generate pdf
=============

Using the command ``pdflatex`` in repository's home directory with main file will generate whole notebook pdf:

        $ pdflatex MSWL_ECO_main.tex

And see output log for compiling errors.



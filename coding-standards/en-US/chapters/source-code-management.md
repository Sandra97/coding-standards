Source Code Management
======================

Before we start talking about what code should look like, it is
appropriate to look at how and where the source code is stored. All
serious software projects, whether driven by an Open Source community or
developed within a company for proprietary purposes will manage the
source code is some sort of source or version management system. Joomla
currently employs two different systems. One system is for the files
that form the product distributed as the Joomla CMS, and the other is
for the files that are distributed as the Joomla Platform. Each system
is described below.

The Joomla Platform
===================

In April 2011 the Joomla project decided to formally split off the core
engine that drives the Joomla CMS into a separate project with a
separate development path called the Joomla Platform. The Joomla
Platform is a PHP framework that is designed to serve as a foundation
for not only web applications (like a CMS) but other types of software
such as command line applications. The files that form the Joomla
Platform are stored in a Distributed Version Control System (DVCS)
called Git hosted at github.org

You can learn about how to get the Joomla Platform source code from the
Git repository from the following page: \<permalink to
developer.joomla.org staging page\>

Because Git treats the concepts of file revision numbers differently
than Subversion, the repository revision number is not required in files
(that is, the @version tag is not necessary).

Compliance Tool
===============

TODO Mention something about CodeSniffer and the custom Joomla sniff
standard for PHP files. The Sniff is based on the standard outlined in
this document. For more information about how code standards are
enforced see the analysis appendix of the manual.
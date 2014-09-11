svn2cvs
=======

Migration tools to upgrade SVN repos to CVS


Rationale
=========

CVS + pserver is actually more scalable and simpler to deliver than Subversion.  Coupled
with an easier HA architecture, an upgrade from SVN to CVS makes sense - especially
since SVN never really properly solved merging or atomic commits in a rational fashion.

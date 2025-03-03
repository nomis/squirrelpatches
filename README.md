# squirrelpatches
Patches for Squirrelmail

what
====

The development of Squirrelmail has been slow lately. No release happened for a long time,
though some development still happens in the subversion repository.

I'm sharing a few patches here with the goal to:

* Fix known security issues.
* Avoid PHP warnings.
* Fix compatibility issues with the current PHP 7.3/7.4.

All these patches have been sent to the squirrelmail developer as well, so I hope this
patch collection can be obsolete soon.

Each patch contains a brief explanation what it does.

Please apply these patches on top of a recent "Stable version snapshot (1.4.23-svn)" from

 https://squirrelmail.org/download.php

Don't use squirrelmail 1.4.22. It contains several severe security vulnerabilities.
Use a version after 2019-07-25 for the latest security fix (CVE-2019-12970).

ProcessWire Environments
===================

_**IN DEVELOPMENT!**_

Processwire module for using multiple environments for a site.

This will create the ability to add a new environment for different situations like local, staging, development, etc. The naming scheme will be anything available that is not a reserved name.

The idea is that a new folder will be created inside of the "site" directory called "config" in which new files can be created for each state. For example you would create a "local.php" file that would store the database information and the $config->httpHosts for that domain (for example processwire-environments.site).


Copyright 2014 by Art Armstrong

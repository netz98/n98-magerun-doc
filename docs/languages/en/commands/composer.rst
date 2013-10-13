Composer Commands
#################

composer:diagnose
*****************


Diagnoses the system to identify common errors.

The &amp;lt;info&amp;gt;diagnose&amp;lt;/info&amp;gt; command checks common errors to help debugging problems.


Usage:

.. code-block:: sh

   $ n98-magerun.phar composer:diagnose


Options
=======

`--help`

   Description:
       Display this help message.

   Shortcut:
       -h

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--quiet`

   Description:
       Do not output any message.

   Shortcut:
       -q

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--verbose`

   Description:
       Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

   Shortcut:
       -v|-vv|-vvv

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--version`

   Description:
       Display this application version.

   Shortcut:
       -V

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--ansi`

   Description:
       Force ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-ansi`

   Description:
       Disable ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-interaction`

   Description:
       Do not ask any interactive question.

   Shortcut:
       -n

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--root-dir`

   Description:
       Force magento root dir. No auto detection

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a


composer:init
*************


Creates a basic composer.json file in current directory.

The &amp;lt;info&amp;gt;init&amp;lt;/info&amp;gt; command creates a basic composer.json file
in the current directory.

&amp;lt;info&amp;gt;php composer.phar init&amp;lt;/info&amp;gt;


Usage:

.. code-block:: sh

   $ n98-magerun.phar composer:init [--name=&amp;quot;...&amp;quot;] [--description=&amp;quot;...&amp;quot;] [--author=&amp;quot;...&amp;quot;] [--homepage=&amp;quot;...&amp;quot;] [--require=&amp;quot;...&amp;quot;] [--require-dev=&amp;quot;...&amp;quot;] [-s|--stability=&amp;quot;...&amp;quot;] [-l|--license=&amp;quot;...&amp;quot;]


Options
=======

`--name`

   Description:
       Name of the package

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--description`

   Description:
       Description of package

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--author`

   Description:
       Author name of package

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--homepage`

   Description:
       Homepage of package

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--require`

   Description:
       Package to require with a version constraint, e.g. foo/bar:1.0.0 or foo/bar=1.0.0 or &amp;quot;foo/bar 1.0.0&amp;quot;

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--require-dev`

   Description:
       Package to require for development with a version constraint, e.g. foo/bar:1.0.0 or foo/bar=1.0.0 or &amp;quot;foo/bar 1.0.0&amp;quot;

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--stability`

   Description:
       Minimum stability (empty or one of: stable, RC, beta, alpha, dev)

   Shortcut:
       -s

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--license`

   Description:
       License of package

   Shortcut:
       -l

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--help`

   Description:
       Display this help message.

   Shortcut:
       -h

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--quiet`

   Description:
       Do not output any message.

   Shortcut:
       -q

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--verbose`

   Description:
       Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

   Shortcut:
       -v|-vv|-vvv

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--version`

   Description:
       Display this application version.

   Shortcut:
       -V

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--ansi`

   Description:
       Force ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-ansi`

   Description:
       Disable ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-interaction`

   Description:
       Do not ask any interactive question.

   Shortcut:
       -n

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--root-dir`

   Description:
       Force magento root dir. No auto detection

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a


composer:install
****************


Installs the project dependencies from the composer.lock file if present, or falls back on the composer.json.

The &amp;lt;info&amp;gt;install&amp;lt;/info&amp;gt; command reads the composer.lock file from
the current directory, processes it, and downloads and installs all the
libraries and dependencies outlined in that file. If the file does not
exist it will look for composer.json and do the same.

&amp;lt;info&amp;gt;php composer.phar install&amp;lt;/info&amp;gt;


Usage:

.. code-block:: sh

   $ n98-magerun.phar composer:install [--prefer-source] [--prefer-dist] [--dry-run] [--dev] [--no-dev] [--no-plugins] [--no-custom-installers] [--no-scripts] [--no-progress] [-v|vv|vvv|--verbose] [-o|--optimize-autoloader]


Options
=======

`--prefer-source`

   Description:
       Forces installation from package sources when possible, including VCS information.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--prefer-dist`

   Description:
       Forces installation from package dist even for dev versions.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--dry-run`

   Description:
       Outputs the operations but will not execute anything (implicitly enables --verbose).

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--dev`

   Description:
       Enables installation of require-dev packages (enabled by default, only present for BC).

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-dev`

   Description:
       Disables installation of require-dev packages.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-plugins`

   Description:
       Disables all plugins.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-custom-installers`

   Description:
       DEPRECATED: Use no-plugins instead.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-scripts`

   Description:
       Skips the execution of all scripts defined in composer.json file.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-progress`

   Description:
       Do not output download progress.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--verbose`

   Description:
       Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

   Shortcut:
       -v|-vv|-vvv

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--optimize-autoloader`

   Description:
       Optimize autoloader during autoloader dump

   Shortcut:
       -o

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--help`

   Description:
       Display this help message.

   Shortcut:
       -h

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--quiet`

   Description:
       Do not output any message.

   Shortcut:
       -q

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--version`

   Description:
       Display this application version.

   Shortcut:
       -V

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--ansi`

   Description:
       Force ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-ansi`

   Description:
       Disable ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-interaction`

   Description:
       Do not ask any interactive question.

   Shortcut:
       -n

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--root-dir`

   Description:
       Force magento root dir. No auto detection

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a


composer:require
****************


Adds required packages to your composer.json and installs them

The require command adds required packages to your composer.json and installs them

If you do not want to install the new dependencies immediately you can call it with --no-update


Usage:

.. code-block:: sh

   $ n98-magerun.phar composer:require [--dev] [--prefer-source] [--prefer-dist] [--no-progress] [--no-update] [packages1] ... [packagesN]

Arguments
=========

`packages`

  Is required:
     No

  Is array:
     Yes

  Description:
     Required package with a version constraint, e.g. foo/bar:1.0.0 or foo/bar=1.0.0 or &amp;quot;foo/bar 1.0.0&amp;quot;

  Default:
    n/a



Options
=======

`--dev`

   Description:
       Add requirement to require-dev.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--prefer-source`

   Description:
       Forces installation from package sources when possible, including VCS information.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--prefer-dist`

   Description:
       Forces installation from package dist even for dev versions.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-progress`

   Description:
       Do not output download progress.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-update`

   Description:
       Disables the automatic update of the dependencies.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--help`

   Description:
       Display this help message.

   Shortcut:
       -h

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--quiet`

   Description:
       Do not output any message.

   Shortcut:
       -q

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--verbose`

   Description:
       Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

   Shortcut:
       -v|-vv|-vvv

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--version`

   Description:
       Display this application version.

   Shortcut:
       -V

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--ansi`

   Description:
       Force ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-ansi`

   Description:
       Disable ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-interaction`

   Description:
       Do not ask any interactive question.

   Shortcut:
       -n

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--root-dir`

   Description:
       Force magento root dir. No auto detection

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a


composer:search
***************


Search for packages

The search command searches for packages by its name
&amp;lt;info&amp;gt;php composer.phar search symfony composer&amp;lt;/info&amp;gt;


Usage:

.. code-block:: sh

   $ n98-magerun.phar composer:search [-N|--only-name] tokens1 ... [tokensN]

Arguments
=========

`tokens`

  Is required:
     Yes

  Is array:
     Yes

  Description:
     tokens to search for

  Default:
    n/a



Options
=======

`--only-name`

   Description:
       Search only in name

   Shortcut:
       -N

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--help`

   Description:
       Display this help message.

   Shortcut:
       -h

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--quiet`

   Description:
       Do not output any message.

   Shortcut:
       -q

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--verbose`

   Description:
       Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

   Shortcut:
       -v|-vv|-vvv

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--version`

   Description:
       Display this application version.

   Shortcut:
       -V

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--ansi`

   Description:
       Force ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-ansi`

   Description:
       Disable ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-interaction`

   Description:
       Do not ask any interactive question.

   Shortcut:
       -n

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--root-dir`

   Description:
       Force magento root dir. No auto detection

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a


composer:update
***************


Updates your dependencies to the latest version according to composer.json, and updates the composer.lock file.

The &amp;lt;info&amp;gt;update&amp;lt;/info&amp;gt; command reads the composer.json file from the
current directory, processes it, and updates, removes or installs all the
dependencies.

&amp;lt;info&amp;gt;php composer.phar update&amp;lt;/info&amp;gt;

To limit the update operation to a few packages, you can list the package(s)
you want to update as such:

&amp;lt;info&amp;gt;php composer.phar update vendor/package1 foo/mypackage [...]&amp;lt;/info&amp;gt;

Usage:

.. code-block:: sh

   $ n98-magerun.phar composer:update [--prefer-source] [--prefer-dist] [--dry-run] [--dev] [--no-dev] [--lock] [--no-plugins] [--no-custom-installers] [--no-scripts] [--no-progress] [-v|vv|vvv|--verbose] [-o|--optimize-autoloader] [packages1] ... [packagesN]

Arguments
=========

`packages`

  Is required:
     No

  Is array:
     Yes

  Description:
     Packages that should be updated, if not provided all packages are.

  Default:
    n/a



Options
=======

`--prefer-source`

   Description:
       Forces installation from package sources when possible, including VCS information.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--prefer-dist`

   Description:
       Forces installation from package dist even for dev versions.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--dry-run`

   Description:
       Outputs the operations but will not execute anything (implicitly enables --verbose).

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--dev`

   Description:
       Enables installation of require-dev packages (enabled by default, only present for BC).

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-dev`

   Description:
       Disables installation of require-dev packages.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--lock`

   Description:
       Only updates the lock file hash to suppress warning about the lock file being out of date.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-plugins`

   Description:
       Disables all plugins.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-custom-installers`

   Description:
       DEPRECATED: Use no-plugins instead.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-scripts`

   Description:
       Skips the execution of all scripts defined in composer.json file.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-progress`

   Description:
       Do not output download progress.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--verbose`

   Description:
       Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

   Shortcut:
       -v|-vv|-vvv

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--optimize-autoloader`

   Description:
       Optimize autoloader during autoloader dump

   Shortcut:
       -o

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--help`

   Description:
       Display this help message.

   Shortcut:
       -h

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--quiet`

   Description:
       Do not output any message.

   Shortcut:
       -q

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--version`

   Description:
       Display this application version.

   Shortcut:
       -V

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--ansi`

   Description:
       Force ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-ansi`

   Description:
       Disable ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-interaction`

   Description:
       Do not ask any interactive question.

   Shortcut:
       -n

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--root-dir`

   Description:
       Force magento root dir. No auto detection

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a


composer:validate
*****************


Validates a composer.json

The validate command validates a given composer.json


Usage:

.. code-block:: sh

   $ n98-magerun.phar composer:validate [file]

Arguments
=========

`file`

  Is required:
     No

  Is array:
     No

  Description:
     path to composer.json file

  Default:
    ./composer.json



Options
=======

`--help`

   Description:
       Display this help message.

   Shortcut:
       -h

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--quiet`

   Description:
       Do not output any message.

   Shortcut:
       -q

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--verbose`

   Description:
       Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

   Shortcut:
       -v|-vv|-vvv

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--version`

   Description:
       Display this application version.

   Shortcut:
       -V

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--ansi`

   Description:
       Force ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-ansi`

   Description:
       Disable ANSI output.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-interaction`

   Description:
       Do not ask any interactive question.

   Shortcut:
       -n

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--root-dir`

   Description:
       Force magento root dir. No auto detection

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a



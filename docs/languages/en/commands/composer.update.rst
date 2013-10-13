composer:update
###############


Updates your dependencies to the latest version according to composer.json, and updates the composer.lock file.

The &lt;info&gt;update&lt;/info&gt; command reads the composer.json file from the
current directory, processes it, and updates, removes or installs all the
dependencies.

&lt;info&gt;php composer.phar update&lt;/info&gt;

To limit the update operation to a few packages, you can list the package(s)
you want to update as such:

&lt;info&gt;php composer.phar update vendor/package1 foo/mypackage [...]&lt;/info&gt;

Usage:

.. code-block:: sh

   $ n98-magerun.phar composer:update [--prefer-source] [--prefer-dist] [--dry-run] [--dev] [--no-dev] [--lock] [--no-plugins] [--no-custom-installers] [--no-scripts] [--no-progress] [-v|vv|vvv|--verbose] [-o|--optimize-autoloader] [packages1] ... [packagesN]

Arguments
---------

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
-------

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



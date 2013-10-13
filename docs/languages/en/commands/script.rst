Script Commands
###############

script:repo:list
****************


Lists all scripts in repository

You can organize your scripts in a repository.
Simply place a script in folder */usr/local/share/n98-magerun/scripts* or in your home dir
in folder *&amp;lt;HOME&amp;gt;/.n98-magerun/scripts*.

Scripts must have the file extension *.magerun*.

After that you can list all scripts with the *script:repo:list* command.
The first line of the script can contain a comment (line prefixed with #) which will be displayed as description.

   $ n98-magerun.phar script:repo:list

Usage:

.. code-block:: sh

   $ n98-magerun.phar script:repo:list


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


script:repo:run
***************


Run script from repository



Usage:

.. code-block:: sh

   $ n98-magerun.phar script:repo:run [script]

Arguments
=========

`script`

  Is required:
     No

  Is array:
     No

  Description:
     Name of script in repository

  Default:
    n/a



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



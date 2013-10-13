dev:module:create
#################


Create and register a new magento module.



Usage:

.. code-block:: sh

   $ n98-magerun.phar dev:module:create [--add-blocks] [--add-helpers] [--add-models] [--add-setup] [--add-all] [--modman] [--add-readme] [--add-composer] [--author-name[=&quot;...&quot;]] [--author-email[=&quot;...&quot;]] [--description[=&quot;...&quot;]] vendorNamespace moduleName [codePool]

Arguments
---------

`vendorNamespace`

  Is required:
     Yes

  Is array:
     No

  Description:
     Namespace (your company prefix)

  Default:
            n/a
    
`moduleName`

  Is required:
     Yes

  Is array:
     No

  Description:
     Name of your module.

  Default:
            n/a
    
`codePool`

  Is required:
     No

  Is array:
     No

  Description:
     Codepool (local,community)

  Default:
            local
    


Options
-------

`--add-blocks`

   Description:
       Adds blocks

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--add-helpers`

   Description:
       Adds helpers

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--add-models`

   Description:
       Adds models

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--add-setup`

   Description:
       Adds SQL setup

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--add-all`

   Description:
       Adds blocks, helpers and models

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--modman`

   Description:
       Create all files in folder with a modman file.

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--add-readme`

   Description:
       Adds a readme.md file to generated module

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--add-composer`

   Description:
       Adds a composer.json file to generated module

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--author-name`

   Description:
       Author for readme.md or composer.json

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--author-email`

   Description:
       Author for readme.md or composer.json

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
       Description for readme.md or composer.json

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



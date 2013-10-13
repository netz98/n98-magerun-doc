help
####


Displays help for a command

The &lt;info&gt;help&lt;/info&gt; command displays help for a given command:

  &lt;info&gt;php /home/cmuench/Workspaces/PHP/opensource/n98-magerun/bin/n98-magerun help list&lt;/info&gt;

You can also output the help in other formats by using the &lt;comment&gt;--format&lt;/comment&gt; option:

  &lt;info&gt;php /home/cmuench/Workspaces/PHP/opensource/n98-magerun/bin/n98-magerun help --format=xml list&lt;/info&gt;

To display the list of available commands, please use the &lt;info&gt;list&lt;/info&gt; command.

Usage:

.. code-block:: sh

   $ n98-magerun.phar help [--xml] [--format=&quot;...&quot;] [--raw] [command_name]

Arguments
---------

`command_name`

  Is required:
     No

  Is array:
     No

  Description:
     The command name

  Default:
            help
    


Options
-------

`--xml`

   Description:
       To output help as XML

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--format`

   Description:
       To output help in other formats

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--raw`

   Description:
       To output raw command help

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



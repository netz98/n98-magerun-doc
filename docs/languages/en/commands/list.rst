list
####


Lists commands

The &lt;info&gt;list&lt;/info&gt; command lists all commands:

  &lt;info&gt;php /home/cmuench/Workspaces/PHP/opensource/n98-magerun/bin/n98-magerun list&lt;/info&gt;

You can also display the commands for a specific namespace:

  &lt;info&gt;php /home/cmuench/Workspaces/PHP/opensource/n98-magerun/bin/n98-magerun list test&lt;/info&gt;

You can also output the information in other formats by using the &lt;comment&gt;--format&lt;/comment&gt; option:

  &lt;info&gt;php /home/cmuench/Workspaces/PHP/opensource/n98-magerun/bin/n98-magerun list --format=xml&lt;/info&gt;

It&#039;s also possible to get raw list of commands (useful for embedding command runner):

  &lt;info&gt;php /home/cmuench/Workspaces/PHP/opensource/n98-magerun/bin/n98-magerun list --raw&lt;/info&gt;

Usage:

.. code-block:: sh

   $ n98-magerun.phar list [--xml] [--raw] [--format=&quot;...&quot;] [namespace]

Arguments
---------

`namespace`

  Is required:
     No

  Is array:
     No

  Description:
     The namespace name

  Default:
            n/a
    


Options
-------

`--xml`

   Description:
       To output list as XML

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
       To output raw command list

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
       To output list in other formats

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a



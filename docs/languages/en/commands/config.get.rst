config:get
##########


Get a core config item

If &lt;info&gt;path&lt;/info&gt; is not set, all available config items will be listed.
The &lt;info&gt;path&lt;/info&gt; may contain wildcards (*).
If &lt;info&gt;path&lt;/info&gt; ends with a trailing slash, all child items will be listed. E.g.

    config:get web/ 
is the same as
    config:get web/*

Usage:

.. code-block:: sh

   $ n98-magerun.phar config:get [--scope=&quot;...&quot;] [--scope-id=&quot;...&quot;] [--decrypt] [--update-script] [--magerun-script] [path]

Arguments
---------

`path`

  Is required:
     No

  Is array:
     No

  Description:
     The config path

  Default:
            n/a
    


Options
-------

`--scope`

   Description:
       The config value&#039;s scope

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--scope-id`

   Description:
       The config value&#039;s scope ID

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--decrypt`

   Description:
       Decrypt the config value using local.xml&#039;s crypt key

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--update-script`

   Description:
       Output as update script lines

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--magerun-script`

   Description:
       Output for usage with config:set

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



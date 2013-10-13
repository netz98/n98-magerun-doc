Standalone Commands
###################

help
****


Displays help for a command

The &amp;lt;info&amp;gt;help&amp;lt;/info&amp;gt; command displays help for a given command:

  &amp;lt;info&amp;gt;php /home/cmuench/Workspaces/PHP/opensource/n98-magerun/bin/n98-magerun help list&amp;lt;/info&amp;gt;

You can also output the help in other formats by using the &amp;lt;comment&amp;gt;--format&amp;lt;/comment&amp;gt; option:

  &amp;lt;info&amp;gt;php /home/cmuench/Workspaces/PHP/opensource/n98-magerun/bin/n98-magerun help --format=xml list&amp;lt;/info&amp;gt;

To display the list of available commands, please use the &amp;lt;info&amp;gt;list&amp;lt;/info&amp;gt; command.

Usage:

.. code-block:: sh

   $ n98-magerun.phar help [--xml] [--format=&amp;quot;...&amp;quot;] [--raw] [command_name]

Arguments
=========

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
=======

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


install
*******


Install magento

* Download Magento by a list of git repos and zip files (mageplus, magelte, official community packages).
* Try to create database if it does not exist.
* Installs Magento sample data if available (since version 1.2.0).
* Starts Magento installer
* Sets rewrite base in .htaccess file

Example of an unattended Magento CE 1.7.0.2 installation:

   $ n98-magerun.phar install --dbHost=&amp;quot;localhost&amp;quot; --dbUser=&amp;quot;mydbuser&amp;quot; --dbPass=&amp;quot;mysecret&amp;quot; --dbName=&amp;quot;magentodb&amp;quot; --installSampleData=yes --useDefaultConfigParams=yes --magentoVersionByName=&amp;quot;magento-ce-1.7.0.2&amp;quot; --installationFolder=&amp;quot;magento&amp;quot; --baseUrl=&amp;quot;http://magento.localdomain/&amp;quot;

See it in action: http://youtu.be/WU-CbJ86eQc


Usage:

.. code-block:: sh

   $ n98-magerun.phar install [--magentoVersion[=&amp;quot;...&amp;quot;]] [--magentoVersionByName[=&amp;quot;...&amp;quot;]] [--installationFolder[=&amp;quot;...&amp;quot;]] [--dbHost[=&amp;quot;...&amp;quot;]] [--dbUser[=&amp;quot;...&amp;quot;]] [--dbPass[=&amp;quot;...&amp;quot;]] [--dbName[=&amp;quot;...&amp;quot;]] [--installSampleData[=&amp;quot;...&amp;quot;]] [--useDefaultConfigParams[=&amp;quot;...&amp;quot;]] [--baseUrl[=&amp;quot;...&amp;quot;]] [--replaceHtaccessFile[=&amp;quot;...&amp;quot;]]


Options
=======

`--magentoVersion`

   Description:
       Magento version

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--magentoVersionByName`

   Description:
       Magento version name instead of order number

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--installationFolder`

   Description:
       Installation folder

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--dbHost`

   Description:
       Database host

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--dbUser`

   Description:
       Database user

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--dbPass`

   Description:
       Database password

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--dbName`

   Description:
       Database name

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--installSampleData`

   Description:
       Install sample data

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--useDefaultConfigParams`

   Description:
       Use default installation parameters defined in the yaml file

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--baseUrl`

   Description:
       Installation base url

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--replaceHtaccessFile`

   Description:
       Generate htaccess file (for non vhost environment)

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


list
****


Lists commands

The &amp;lt;info&amp;gt;list&amp;lt;/info&amp;gt; command lists all commands:

  &amp;lt;info&amp;gt;php /home/cmuench/Workspaces/PHP/opensource/n98-magerun/bin/n98-magerun list&amp;lt;/info&amp;gt;

You can also display the commands for a specific namespace:

  &amp;lt;info&amp;gt;php /home/cmuench/Workspaces/PHP/opensource/n98-magerun/bin/n98-magerun list test&amp;lt;/info&amp;gt;

You can also output the information in other formats by using the &amp;lt;comment&amp;gt;--format&amp;lt;/comment&amp;gt; option:

  &amp;lt;info&amp;gt;php /home/cmuench/Workspaces/PHP/opensource/n98-magerun/bin/n98-magerun list --format=xml&amp;lt;/info&amp;gt;

It&amp;#039;s also possible to get raw list of commands (useful for embedding command runner):

  &amp;lt;info&amp;gt;php /home/cmuench/Workspaces/PHP/opensource/n98-magerun/bin/n98-magerun list --raw&amp;lt;/info&amp;gt;

Usage:

.. code-block:: sh

   $ n98-magerun.phar list [--xml] [--raw] [--format=&amp;quot;...&amp;quot;] [namespace]

Arguments
=========

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
=======

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


open-browser
************


Open current project in browser &amp;lt;comment&amp;gt;(experimental)&amp;lt;/comment&amp;gt;



Usage:

.. code-block:: sh

   $ n98-magerun.phar open-browser [store]

Arguments
=========

`store`

  Is required:
     No

  Is array:
     No

  Description:
     Store code or ID

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


script
******


Runs multiple n98-magerun commands

Example:

   # Set multiple config
   config:set &amp;quot;web/cookie/cookie_domain&amp;quot; example.com

   # Set with multiline values with &amp;quot;
&amp;quot;
   config:set &amp;quot;general/store_information/address&amp;quot; &amp;quot;First line
Second line
Third line&amp;quot;

   # This is a comment
   cache:flush


Optionally you can work with unix pipes.

   $ echo &amp;quot;cache:flush&amp;quot; | n98-magerun-dev script

   $ n98-magerun.phar script &amp;lt; filename

It is even possible to create executable scripts:

Create file `test.magerun` and make it executable (`chmod +x test.magerun`):

   #!/usr/bin/env n98-magerun.phar script

   config:set &amp;quot;web/cookie/cookie_domain&amp;quot; example.com
   cache:flush

   # Run a shell script with &amp;quot;!&amp;quot; as first char
   ! ls -l

   # Register your own variable (only key = value currently supported)
   ${my.var}=bar

   # Let magerun ask for variable value - add a question mark
   ${my.var}=?

   ! echo ${my.var}

   # Use resolved variables from n98-magerun in shell commands
   ! ls -l ${magento.root}/code/local

Pre-defined variables:

* ${magento.root}    -&amp;gt; Magento Root-Folder
* ${magento.version} -&amp;gt; Magento Version i.e. 1.7.0.2
* ${magento.edition} -&amp;gt; Magento Edition -&amp;gt; Community or Enterprise
* ${magerun.version} -&amp;gt; Magerun version i.e. 1.66.0
* ${php.version}     -&amp;gt; PHP Version
* ${script.file}     -&amp;gt; Current script file path
* ${script.dir}      -&amp;gt; Current script file dir

Variables can be passed to a script with &amp;quot;--define (-d)&amp;quot; option.

Example:

   $ n98-magerun.phar script -d foo=bar filename

   # This will register the variable ${foo} with value bar.

It&amp;#039;s possible to define multiple values by passing more than one option.

Usage:

.. code-block:: sh

   $ n98-magerun.phar script [-d|--define[=&amp;quot;...&amp;quot;]] [filename]

Arguments
=========

`filename`

  Is required:
     No

  Is array:
     No

  Description:
     Script file

  Default:
    n/a



Options
=======

`--define`

   Description:
       Defines a variable

   Shortcut:
       -d

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


shell
*****


Runs n98-magerun as shell



Usage:

.. code-block:: sh

   $ n98-magerun.phar shell


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


uninstall
*********


Uninstall magento (drops database and empties current folder

**Please be careful: This removes all data from your installation.**

Usage:

.. code-block:: sh

   $ n98-magerun.phar uninstall [-f|--force]


Options
=======

`--force`

   Description:
       Force

   Shortcut:
       -f

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



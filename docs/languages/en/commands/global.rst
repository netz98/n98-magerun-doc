Global
======

help
----

-  Description: Displays help for a command
-  Usage: ``help [--xml] [--format="..."] [--raw] [command_name]``
-  Aliases:

The help command displays help for a given command:

php n98-magerun.phar help list

You can also output the help in other formats by using the --format
option:

php n98-magerun.phar help --format=xml list

To display the list of available commands, please use the list command.

Arguments:
~~~~~~~~~~

**command:**

-  Name: command
-  Is required: yes
-  Is array: no
-  Description: The command to execute
-  Default: ``NULL``

**command\_name:**

-  Name: command\_name
-  Is required: no
-  Is array: no
-  Description: The command name
-  Default: ``'help'``

Options:
~~~~~~~~

**xml:**

-  Name: ``--xml``
-  Shortcut:
-  Accept value: no
-  Is value required: no
-  Is multiple: no
-  Description: To output help as XML
-  Default: ``false``

**format:**

-  Name: ``--format``
-  Shortcut:
-  Accept value: yes
-  Is value required: yes
-  Is multiple: no
-  Description: To output help in other formats
-  Default: ``NULL``

**raw:**

-  Name: ``--raw``
-  Shortcut:
-  Accept value: no
-  Is value required: no
-  Is multiple: no
-  Description: To output raw command help
-  Default: ``false``

**help:**

-  Name: ``--help``
-  Shortcut: ``-h``
-  Accept value: no
-  Is value required: no
-  Is multiple: no
-  Description: Display this help message.
-  Default: ``false``

**quiet:**

-  Name: ``--quiet``
-  Shortcut: ``-q``
-  Accept value: no
-  Is value required: no
-  Is multiple: no
-  Description: Do not output any message.
-  Default: ``false``

**verbose:**

-  Name: ``--verbose``
-  Shortcut: ``-v|-vv|-vvv``
-  Accept value: no
-  Is value required: no
-  Is multiple: no
-  Description: Increase the verbosity of messages: 1 for normal output,
   2 for more verbose output and 3 for debug
-  Default: ``false``

**version:**

-  Name: ``--version``
-  Shortcut: ``-V``
-  Accept value: no
-  Is value required: no
-  Is multiple: no
-  Description: Display this application version.
-  Default: ``false``

**ansi:**

-  Name: ``--ansi``
-  Shortcut:
-  Accept value: no
-  Is value required: no
-  Is multiple: no
-  Description: Force ANSI output.
-  Default: ``false``

**no-ansi:**

-  Name: ``--no-ansi``
-  Shortcut:
-  Accept value: no
-  Is value required: no
-  Is multiple: no
-  Description: Disable ANSI output.
-  Default: ``false``

**no-interaction:**

-  Name: ``--no-interaction``
-  Shortcut: ``-n``
-  Accept value: no
-  Is value required: no
-  Is multiple: no
-  Description: Do not ask any interactive question.
-  Default: ``false``

**root-dir:**

-  Name: ``--root-dir``
-  Shortcut:
-  Accept value: yes
-  Is value required: no
-  Is multiple: no
-  Description: Force magento root dir. No auto detection
-  Default: ``NULL``

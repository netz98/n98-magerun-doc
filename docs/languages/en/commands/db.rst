Db Commands
###########

db:console
**********


Opens mysql client by database config from local.xml



Usage:

.. code-block:: sh

   $ n98-magerun.phar db:console


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


db:create
*********


Create currently configured database

The command tries to create the configured database according to your
settings in app/etc/local.xml.
The configured user must have &amp;quot;CREATE DATABASE&amp;quot; privileges on MySQL Server.

Usage:

.. code-block:: sh

   $ n98-magerun.phar db:create


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


db:drop
*******


Drop current database

The command prompts before dropping the database. If --force option is specified it
directly drops the database.
The configured user in app/etc/local.xml must have &amp;quot;DROP&amp;quot; privileges.

Usage:

.. code-block:: sh

   $ n98-magerun.phar db:drop [-f|--force]


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


db:dump
*******


Dumps database with mysqldump cli client according to informations from local.xml

Dumps configured magento database with `mysqldump`.
You must have installed the MySQL client tools.

On debian systems run `apt-get install mysql-client` to do that.

The command reads app/etc/local.xml to find the correct settings.
If you like to skip data of some tables you can use the --strip option.
The strip option creates only the structure of the defined tables and
forces `mysqldump` to skip the data.

Dumps your database and excludes some tables. This is useful i.e. for development.

Separate each table to strip by a space.
You can use wildcards like * and ? in the table names to strip multiple tables.
In addition you can specify pre-defined table groups, that start with an @
Example: &amp;quot;dataflow_batch_export unimportant_module_* @log

   $ n98-magerun.phar db:dump --strip=&amp;quot;@stripped&amp;quot;

Available Table Groups:

* @log Log tables
* @dataflowtemp Temporary tables of the dataflow import/export tool
* @stripped Standard definition for a stripped dump (logs and dataflow)
* @sales Sales data (orders, invoices, creditmemos etc)
* @customers Customer data
* @trade Current trade data (customers and orders). You usally do not want those in developer systems.
* @development Removes logs and trade data so developers do not have to work with real customer data

Extended: https://github.com/netz98/n98-magerun/wiki/Stripped-Database-Dumps

See it in action: http://youtu.be/ttjZHY6vThs

- If you like to prepend a timestamp to the dump name the --add-time option can be used.

- The command comes with a compression function. Add i.e. `--compress=gz` to dump directly in
 gzip compressed file.


&amp;lt;comment&amp;gt;Compression option&amp;lt;/comment&amp;gt;
 Supported compression: gzip
 The gzip cli tool has to be installed.
 Additionally, for data-to-csv option tar cli tool has to be installed too.

&amp;lt;comment&amp;gt;Strip option&amp;lt;/comment&amp;gt;
 Separate each table to strip by a space.
 You can use wildcards like * and ? in the table names to strip multiple tables.
 In addition you can specify pre-defined table groups, that start with an @
 Example: &amp;quot;dataflow_batch_export unimportant_module_* @log

&amp;lt;comment&amp;gt;Available Table Groups&amp;lt;/comment&amp;gt;
 &amp;lt;info&amp;gt;@log&amp;lt;/info&amp;gt; Log tables
 &amp;lt;info&amp;gt;@dataflowtemp&amp;lt;/info&amp;gt; Temporary tables of the dataflow import/export tool
 &amp;lt;info&amp;gt;@stripped&amp;lt;/info&amp;gt; Standard definition for a stripped dump (logs and dataflow)
 &amp;lt;info&amp;gt;@sales&amp;lt;/info&amp;gt; Sales data (orders, invoices, creditmemos etc)
 &amp;lt;info&amp;gt;@customers&amp;lt;/info&amp;gt; Customer data - Should not be used without @sales
 &amp;lt;info&amp;gt;@trade&amp;lt;/info&amp;gt; Current trade data (customers and orders). You usally do not want those in developer systems.
 &amp;lt;info&amp;gt;@development&amp;lt;/info&amp;gt; Removes logs and trade data so developers do not have to work with real customer data
 &amp;lt;info&amp;gt;@ee_changelog&amp;lt;/info&amp;gt; Changelog tables of new indexer since EE 1.13
 &amp;lt;info&amp;gt;@idx&amp;lt;/info&amp;gt; Tables with _idx suffix

Usage:

.. code-block:: sh

   $ n98-magerun.phar db:dump [-t|--add-time[=&amp;quot;...&amp;quot;]] [-c|--compression=&amp;quot;...&amp;quot;] [--only-command] [--print-only-filename] [--no-single-transaction] [--human-readable] [--stdout] [-s|--strip[=&amp;quot;...&amp;quot;]] [-f|--force] [filename]

Arguments
=========

`filename`

  Is required:
     No

  Is array:
     No

  Description:
     Dump filename

  Default:
    n/a



Options
=======

`--add-time`

   Description:
       Adds time to filename (only if filename was not provided)

   Shortcut:
       -t

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--compression`

   Description:
       Compress the dump file using one of the supported algorithms

   Shortcut:
       -c

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--only-command`

   Description:
       Print only mysqldump command. Do not execute

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--print-only-filename`

   Description:
       Execute and prints no output except the dump filename

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--no-single-transaction`

   Description:
       Do not use single-transaction (not recommended, this is blocking)

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--human-readable`

   Description:
       Use a single insert with column names per row. Useful to track database differences, but significantly slows down a later import

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--stdout`

   Description:
       Dump to stdout

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--strip`

   Description:
       Tables to strip (dump only structure of those tables)

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

`--force`

   Description:
       Do not prompt if all options are defined

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


db:import
*********


Imports database with mysql cli client according to database defined in local.xml



Usage:

.. code-block:: sh

   $ n98-magerun.phar db:import [-c|--compression=&amp;quot;...&amp;quot;] [--only-command] [--only-if-empty] [filename]

Arguments
=========

`filename`

  Is required:
     No

  Is array:
     No

  Description:
     Dump filename

  Default:
    n/a



Options
=======

`--compression`

   Description:
       The compression of the specified file

   Shortcut:
       -c

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--only-command`

   Description:
       Print only mysql command. Do not execute

   Shortcut:
       

   Accept value:
       No

   Is value required:
       No

   Is multiple:
       No

   Default:
       n/a

`--only-if-empty`

   Description:
       Imports only if database is empty

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


db:info
*******


Dumps database informations

This command is useful to print all informations about the current configured database in app/etc/local.xml.
It can print connection string for JDBC, PDO connections.

Usage:

.. code-block:: sh

   $ n98-magerun.phar db:info


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


db:query
********


Executes an SQL query on the database defined in local.xml

Executes an SQL query on the current configured database. Wrap your SQL in
single or double quotes.

If your query produces a result (e.g. a SELECT statement), the output of the
mysql cli tool will be returned.

* Requires MySQL CLI tools installed on your system.


Usage:

.. code-block:: sh

   $ n98-magerun.phar db:query [--only-command] [query]

Arguments
=========

`query`

  Is required:
     No

  Is array:
     No

  Description:
     SQL query

  Default:
    n/a



Options
=======

`--only-command`

   Description:
       Print only mysql command. Do not execute

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



db:dump
#######


Dumps database with mysqldump cli client according to informations from local.xml



&lt;comment&gt;Compression option&lt;/comment&gt;
 Supported compression: gzip
 The gzip cli tool has to be installed.
 Additionally, for data-to-csv option tar cli tool has to be installed too.

&lt;comment&gt;Strip option&lt;/comment&gt;
 Separate each table to strip by a space.
 You can use wildcards like * and ? in the table names to strip multiple tables.
 In addition you can specify pre-defined table groups, that start with an @
 Example: &quot;dataflow_batch_export unimportant_module_* @log

&lt;comment&gt;Available Table Groups&lt;/comment&gt;
 &lt;info&gt;@log&lt;/info&gt; Log tables
 &lt;info&gt;@dataflowtemp&lt;/info&gt; Temporary tables of the dataflow import/export tool
 &lt;info&gt;@stripped&lt;/info&gt; Standard definition for a stripped dump (logs and dataflow)
 &lt;info&gt;@sales&lt;/info&gt; Sales data (orders, invoices, creditmemos etc)
 &lt;info&gt;@customers&lt;/info&gt; Customer data - Should not be used without @sales
 &lt;info&gt;@trade&lt;/info&gt; Current trade data (customers and orders). You usally do not want those in developer systems.
 &lt;info&gt;@development&lt;/info&gt; Removes logs and trade data so developers do not have to work with real customer data
 &lt;info&gt;@ee_changelog&lt;/info&gt; Changelog tables of new indexer since EE 1.13
 &lt;info&gt;@idx&lt;/info&gt; Tables with _idx suffix

Usage:

.. code-block:: sh

   $ n98-magerun.phar db:dump [-t|--add-time[=&quot;...&quot;]] [-c|--compression=&quot;...&quot;] [--only-command] [--print-only-filename] [--no-single-transaction] [--human-readable] [--stdout] [-s|--strip[=&quot;...&quot;]] [-f|--force] [filename]

Arguments
---------

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
-------

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



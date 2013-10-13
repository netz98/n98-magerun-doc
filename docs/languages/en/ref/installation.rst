Installation/Update
===================

Installation
------------

There are two ways to install the tools:

Download phar file
""""""""""""""""""

.. code-block:: sh

    wget https://raw.github.com/netz98/n98-magerun/master/n98-magerun.phar

or if you have problems with SSL certificate:

.. code-block:: sh

   curl -o n98-magerun.phar https://raw.github.com/netz98/n98-magerun/master/n98-magerun.phar

You can make the .phar file executable.

.. code-block:: sh

    chmod +x ./n98-magerun.phar

If you want to use command system wide you can copy it to `/usr/local/bin`.

.. code-block:: sh

    sudo cp ./n98-magerun.phar /usr/local/bin/

**Debian / suhosin:**

On some debian systems with compiled in suhosin the phar extension must be added to a whitelist.

Add this to your php.ini file:

.. code-block:: ini

   suhosin.executor.include.whitelist="phar"


**You don't like the filename?**

Just rename it to whatever you want.

Install with Composer
"""""""""""""""""""""

https://github.com/netz98/n98-magerun/wiki/Install-from-source-with-Composer

Update
------

Since version 1.1.0 we deliver a self-update script within the phar file::

   $ n98-magerun.phar self-update

If file was installed system wide do not forget "sudo".

See it in action: http://youtu.be/wMHpfKD9vjM
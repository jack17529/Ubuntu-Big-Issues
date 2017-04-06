Best option is to remove pip !

All other ways either takes too much time or won't work.

This is silver bullet!

Remove old pip by -> "sudo apt-get purge --auto-remove python-pip" 

Or by manually deleting it.

Go to this link - https://www.liquidweb.com/kb/how-to-install-pip-on-ubuntu-14-04-lts/

For me it installed in

vagrant@vagrant-ubuntu-trusty-64:/vagrant$ which pip
/usr/local/bin/pip

So there is a mistake in the post as the command pip --help

will not work.

vagrant@vagrant-ubuntu-trusty-64:/vagrant$ pip --help
-bash: /usr/bin/pip: No such file or directory

But you still have pip installed.

Enjoy!
 

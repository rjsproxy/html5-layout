html5-layout
============

Experimenting with html, css, js, etc.

Still not sure the best way to do this.  Linking the global nodes module into
the local directory feels like a hack, but "sudo npm install -g" is not a done
thing. ::

    $ git clone https://github.com/ticti/html5-layout.git
    $ cd html5-layout
    $ ln -s /usr/local/lib/node_modules . 
    $ sudo npm install
    $ bower install
    $ gulp serve

Install local might be the correct way to do it (untested). ::

    $ git clone https://github.com/ticti/html5-layout.git
    $ cd html5-layout
    $ npm install
    $ bower install
    $ gulp serve




Debian
------

Install. ::

	# apt-get install git npm
	# npm install -g yo generator-gulp-webapp

Other things I already had installed. ::

	# npm install -g bower node-sass 

Normalize can be installed with bower. ::

	$ bower install normalize.css


Init
----

Create new gulp web app including sass, bootstrap and modernizr. ::

	$ yo gulp-webapp

Commands

	$ gulp serve

	$ bower






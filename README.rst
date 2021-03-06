axon-id.github.io
=================

This repository hosts Axon-ID's community website source code. The site
itself is available at http://axon-id.github.io.


Prerequisites
-------------

#. Node.js v4 or higher
#. npm (which comes bundled with node)
#. gulp-gh-pages

To install gulp-gh-pages
    $ npm install --save-dev gulp-gh-pages

Contributing
------------

Since this Web app is hosted on github.io, the 'master' branch must be used to deploy the production-ready app.  
Because of this, all development takes place on the `develop <https://github.com/axon-id/axon-id.github.io/tree/develop>`__ branch.

To start the app
    $ gulp serve

To build the app
    $ gulp build 

To build and preview the production-ready app
    $ gulp serve:dist

To deploy the app
    $ gulp deploy 

Adding new content
------------------

To add new content or to update  old information, please `submit an issue`__.

Alternatively you can `submit a pull request`__ and make it even easier for us to update the site.

__ https://github.com/axon-id/axon-id.github.io/issues
__ https://github.com/axon-id/axon-id.github.io/pulls

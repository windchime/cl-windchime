cl-windchime
============

cl-windchime aimes to be a port of Clojure's Noir to Common Lisp.

The name is a pun on "a list of bottles" where list is an obvious reference and
"bottles" points to the Python micro-webframeworks `bottle`_, `flask`_, and
`klein`_ (because a string of bottles is *obviously* a windchime...).

cl-windchime will use the following:

* `cl-spasm`_ for HTML-generation and templating (under development)

* `clack`_ to support HTTP middle-ware

* `cl-routes`_ or `cl-poise`_ (not implemented yet) for routing

* and `Hunchentoot`_ as a dev server and production server fronted by
  `lighttpd`_.

.. Links:
.. _bottle: http://bottlepy.org/
.. _flask: http://flask.pocoo.org/
.. _klein: https://github.com/twisted/klein
.. _cl-spasm: https://github.com/windchime/cl-spasm
.. _clack: http://clacklisp.org/
.. _cl-routes: https://github.com/archimag/cl-routes
.. _cl-poise: https://github.com/windchime/cl-poise
.. _Hunchentoot: http://weitz.de/hunchentoot/
.. _lighttpd: http://www.lighttpd.net/

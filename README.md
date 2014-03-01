Openshift Deck.js Quickstart
============================

[Deck.js](http://imakewebthings.com/deck.js/) helps you make modern HTML presentations.

Running on Openshift
--------------------

Create an account at http://openshift.redhat.com

Create the application (piggybacking on php-5.3)

    rhc app create slides php-5.3 --from-code=git://github.com/abutcher/openshift-deckjs-quickstart.git

Move into your newly cloned application repository, start editing `php/index.html` and `git push` to profit.

License
----

MIT

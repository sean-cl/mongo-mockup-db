.. :changelog:

Changelog
=========

1.1.0 (2016-02-11)
------------------

Add cursor_id property to OpGetMore, and ssl parameter to interactive_server.

1.0.3 (2015-09-12)
------------------

``MockupDB(auto_ismaster=True)`` had just responded ``{"ok": 1}``, but this
isn't enough to convince PyMongo 3 it's talking to a valid standalone,
so auto-respond ``{"ok": 1, "ismaster": True}``.

1.0.2 (2015-09-11)
------------------

Restore Request.assert_matches method, used in pymongo-mockup-tests.

1.0.1 (2015-09-11)
------------------

Allow co-installation with PyMongo.

1.0.0 (2015-09-10)
------------------

First release.

0.1.0 (2015-02-25)
------------------

Development begun.

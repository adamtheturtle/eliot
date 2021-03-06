Eliot: Logging as Storytelling
==============================

Eliot provides a structured logging system for Python that generates as a forest
of nested actions. Action start and eventually finish, successfully or not. Log
messages thus tell a story: what happened, and what caused it.

Features:

* Structured, typed messages.
* Action tree, with messages automatically figuring out their action context.
* Excellent support for unit testing your logging code.
* Twisted support.
* JSON output, usable by Logstash/Elasticsearch.
* Supports Python 2.7 and 3.3.

This is a **PREVIEW** and does not guarantee version stability across versions.

Eliot is released by `HybridCluster`_ under the Apache 2.0 License
and maintained by Itamar Turner-Trauring.

Downloads are available on `PyPI`_.

Documentation can be found on `Read The Docs`_.

Bugs and feature requests should be filed at the project `Github page`_.

.. _Read the Docs: https://eliot.readthedocs.org/
.. _Github page: https://github.com/hybridcluster/eliot
.. _PyPI: https://pypi.python.org/pypi/eliot
.. _HybridCluster: http://www.hybridcluster.com

.. image:: https://travis-ci.org/hybridcluster/eliot.png?branch=master
           :target: http://travis-ci.org/hybridcluster/eliot
           :alt: Build Status

.. _-mapRejections-:

mapRejections
=============

Transforms the list of rejections the inner route produced.

Signature
---------

.. includecode:: /../spray-routing/src/main/scala/spray/routing/directives/BasicDirectives.scala
   :snippet: mapRejections

Description
-----------

The ``mapRejections`` directive is used as a building block for :ref:`Custom Directives` to transform a list
of rejections from the inner route to a new list of rejections.

See :ref:`Response Transforming Directives` for similar directives.

Example
-------

.. includecode:: ../code/docs/directives/BasicDirectivesExamplesSpec.scala
   :snippet: mapRejections

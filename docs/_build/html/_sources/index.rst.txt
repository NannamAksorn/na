.. na documentation master file, created by
   sphinx-quickstart on Mon Sep  2 14:04:00 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. |br| raw:: html

   <br />

NA
==============================

.. toctree::
   :maxdepth: 2
   :caption: Contents:


Table of Contents
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


Naming Convention
==================

***************
CSS
***************

BEM - Block Element Modifier

**Block:** Standalone entity `(card)` |br|
**Element:** Part of a block `(image)` |br|
**Modifier:** Flag on a block or element `(dark, disabled)` |br|

.block__element--modifier |br|
.block--modifier |br|


Example
^^^^^^^^^^^^^^^^^^^^^

HTML

.. code-block:: html

    <div class="my-block my-block--state-good">
        <img class="my-block__image--tall" />
    </div>

CSS

.. code-block:: css

    .my-block { ... }
    .my-block--state-good { … }
    .my-block__image--tall { … }  








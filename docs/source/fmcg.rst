
Fmcg Current Price Documentation
=====

**Admin** Currentprice is the platform used to Create/ Edit/ Duplicate/ Delete the following :

Surveys 
Categories
Brands
Locations
View Users


.. _installation:

Installation
------------

To use the admin, first install it using pip:

.. code-block:: console

   (.venv) $ npm install
   
   
   
Architecture & Design
----------------


Payment Architecture
----------------


User Story Description
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError


Product User Documentation
----------------

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

Quick Start Guide
----------------


Embeded Assistance
----------------

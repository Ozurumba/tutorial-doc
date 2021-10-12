
Database CurrentPrice Documentation
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

Creating recipes
----------------

.. image:: https://res.cloudinary.com/dpsujx7rk/image/upload/v1634031978/word-image-6_vvxuqi.png
  :width: 600
  :height: 400
  :alt: Alternative text

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']




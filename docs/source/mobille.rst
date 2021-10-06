
Mobile App Documentation
=====

**Mobile** Currentprice is the platform used by currentprice agents/ surveyors in different geolocations in different states to do the following :

Fill Surveys 
Capture Real time images of commodities / brands
Update real time Prices of brands
Notify company on new brands or commodities in the market
Make comments of commodities / brands



.. image:: https://res.cloudinary.com/dpsujx7rk/image/upload/v1633503626/WhatsApp_Image_2021-10-05_at_11.53.11_llxtm1.jpg
  :width: 600
  :alt: Alternative text


.. _installation:

Installation
------------

To use the mobile, first install it using npm:

.. code-block:: console

   $ npm install

Creating recipes
----------------

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



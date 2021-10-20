
Fmcg Current Price Documentation
=====

**Fmcg** Currentprice is the platform used to Create/ Edit/ Duplicate/ Delete the following :

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

  $ npm install
   
   
   
Architecture & Design
----------------


Payment Architecture
----------------
Paystack implementations was done for the payment API

Payments are made based on subscription plans 

User Story Description
----------------



.. autofunction::User Signs Up => User Chooses Subscription => User Chooses Commodities => User Chooses brands => User makes payment 


User can see trended graph on commodities
User can see trended graph on brands
User can see trended graph of commodities against different markets
User can see trended graph of brands in a year

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

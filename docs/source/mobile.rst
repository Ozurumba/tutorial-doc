
Mobile App Documentation
=====

**Mobile** Currentprice is the platform used by currentprice agents/ surveyors in different geolocations in different states to do the following :

Fill Surveys 

Capture Real time images of commodities / brands

Update real time Prices of brands

Notify company on new brands or commodities in the market

Make comments of commodities / brands



.. image:: https://res.cloudinary.com/dpsujx7rk/image/upload/v1633503626/WhatsApp_Image_2021-10-05_at_11.53.11_llxtm1.jpg
  :width: 200
  :height: 400
  :alt: Alternative text


.. _installation:

Installation
------------

To use the mobile, first install it using npm:

.. code-block:: console

   $ npm install
   
To run code on localhost:

.. code-block:: console

   $ ionic serve
   
   
Command to build the ionic application and generate the APK:

.. code-block:: console

   $ ionic cordova platform add android
   $ ionic cordova build android
   

Requirements for generating an Android Apk
----------------

Step 1: Install the Android studio in the system : 
https://developer.android.com/studio

Step 2: Make sure java (JDK)1.8 must be installed and environment variable must be set on the system.

Step 3: Download and install the Gradle, Add the path in the environment. https://gradle.org/next-steps/?version=6.8.2&format=bin

Step 4: Download the tools and install everything which is required to work with the Compilation and building of Ionic project.



.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

Architecture Requirements
----------------

Currentprice Mobile App is ran backend using some core technologies :

Capacitor

Cordova Geolocation

Google Live-Maps

Native Camera

Firebase




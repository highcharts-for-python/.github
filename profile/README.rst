###################################################
The Highcharts for Python Toolkit
###################################################

**High-end data visualization for the Python ecosystem**

The **Highcharts for Python Toolkit** is a set of Python libraries that provide a Python wrapper
for the `Highcharts <https://www.highcharts.com>`__ suite of JavaScript data
visualization libraries, with full integration across the Python ecosystem.

The full toolkit includes support for:

.. list-table::
  :widths: 30 30 30
  :header-rows: 1
  
  * - Python Library
    - JavaScript Library
    - Description
  * - `Highcharts Core for Python <https://github.com/highcharts-for-python/highcharts-core>`__
    - `Highcharts Core <https://www.highcharts.com/products/highcharts/>`__
    - the core Highcharts data visualization library
  * - `Highcharts Stock for Python <https://github.com/highcharts-for-python/highcharts-stock>`__
    - `Highcharts Stock <https://www.highcharts.com/products/stock/>`__
    - the time series visualization extension to Highcharts
  * - `Highcharts Maps for Python <https://github.com/highcharts-for-python/highcharts-maps>`__
    - `Highcharts Maps <https://www.highcharts.com/products/maps/>`__
    - the map visualization extension to Highcharts
  * - `Highcharts Gantt for Python <https://github.com/highcharts-for-python/highcharts-gantt>`__
    - `Highcharts Gantt <https://www.highcharts.com/products/gantt/>`__
    - the Gantt charting extension to Highcharts
  * - all Highcharts for Python libraries
    - the **Highcharts Export Server**
    - enabling the programmatic creation of static (downloadable) data visualizations

The toolkit features native integrations with:

  * **Jupyter Labs/Notebook**. You can now produce high-end and interactive plots and
    renders using the full suite of Highcharts visualization capabilities.
  * **Pandas**. Automatically produce data visualizations from your Pandas dataframes
  * **PySpark**. Automatically produce data visualizations from data in a PySpark
    dataframe.
  * ...and more library-specific integrations, including GeoPandas, PyShp, Topjson, Geojson, Asana, and more

**COMPLETE DOCUMENTATION:** http://core-docs.highchartspython.com/en/latest/index.html

--------------------

***************
Installation
***************

Highcharts Core for Python
=============================

To install **Highcharts Core for Python**, just execute:

  .. code:: bash

   $ pip install highcharts-core

Highcharts Stock for Python
=================================

To install **Highcharts Stock for Python**, just execute:

  .. code:: bash

    $ pip install highcharts-stock

Highcharts Maps for Python
=================================

To install **Highcharts Maps for Python**, just execute:

  .. code:: bash

    $ pip install highcharts-maps

Highcharts Gantt for Python
=================================

To install **Highcharts Gantt for Python**, just execute:

  .. code:: bash

    $ pip install highcharts-gantt

-------------

************************************
Why Highcharts for Python?
************************************

`Highcharts <https://www.highcharts.com>`__ is the world's most popular, most powerful, 
category-defining JavaScript data visualization library. If you are building a web or 
mobile app/dashboard that will be visualizing data in some fashion, you should 
absolutely take a look at the Highcharts suite of solutions. Take a peak at some 
fantastic `demo visualizations <https://www.highcharts.com/demo>`__.

As a suite of JavaScript libraries, `Highcharts <https://www.highcharts.com>`__ is 
written in JavaScript, and is used to configure and render data visualizations in a
web browser (or other JavaScript-executing) environment. As a set of JavaScript
libraries, its audience is JavaScript developers. But what about the broader ecosystem of
Python developers and data scientists?

Given Python's increasing adoption as the technology of choice for data science and for
the backends of leading enterprise-grade applications, Python is often the backend that 
delivers data and content to the front-end...which then renders it using JavaScript and 
HTML.

There are numerous Python frameworks (Django, Flask, Tornado, etc.) with specific
capabilities to simplify integration with Javascript frontend frameworks (React, Angular,
VueJS, etc.). But facilitating that with Highcharts has historically been very difficult.
Part of this difficulty is because the Highcharts JavaScript suite - while supporting JSON as a
serialization/deserialization format - leverages JavaScript object literals to expose the
full power and interactivity of its data visualizations. And while it's easy to serialize
JSON from Python, serializing and deserializing to/from JavaScript object literal notation
is much more complicated. 

This means that Python developers looking to integrate with Highcharts typically had to 
either invest a lot of effort, or were only able to leverage a small portion of Highcharts' 
rich functionality.

So we wrote the **Highcharts for Python** toolkit to bridge that gap.

**Highcharts for Python** provides Python object representation for *all* of the
JavaScript objects defined in the
`Highcharts (JavaScript) API <https://api.highcharts.com/highcharts/>`__. It provides automatic 
data validation, and exposes simple and standardized methods for serializing those Python
objects back-and-forth to JavaScript object literal notation.

Key Highcharts for Python Features
======================================

* **Clean and consistent API**. No reliance on "hacky" code, ``dict``
  and JSON serialization, or impossible to maintain / copy-pasted "spaghetti code".
* **Comprehensive Highcharts Support**. Every single Highcharts chart type and every
  single configuration option is supported in the **Highcharts for Python** toolkit.
  This includes the over 70 data visualization types supported by
  `Highcharts Core <https://www.highcharts.com/product/highcharts/>`__ and the 50+
  technical indicator visualizations available in
  `Highcharts Stock <https://www.highcharts.com/product/stock/>`__, with full support for
  the rich JavaScript formatter (JS callback function) capabilities that are often needed 
  to get the most out of Highcharts' visualization and interaction capabilities.

  **See Also**

    * `Supported Visualizations <https://core-docs.highchartspython.com/en/latest/visualizations.html>`__

* **Simple JavaScript Code Generation**. With one method call, produce production-ready
  JavaScript code to render your interactive visualizations using Highcharts' rich
  capabilities.
* **Easy and Robust Chart Download**. With one method call, produce high-end static
  visualizations that can be downloaded or shared as files with your audience. Produce
  static charts using the Highsoft-provided **Highcharts Export Server**, or using your 
  own private export server as needed.
* **Integration with Pandas and PySpark**. With two lines of code, produce a high-end
  interactive visualization of your Pandas or PySpark dataframe.
* **Consistent code style**. For Python developers, switching between Pythonic code
  conventions and JavaScript code conventions can be...annoying. So
  **Highcharts for Python** applies Pythonic syntax with automatic conversion between
  Pythonic ``snake_case`` notation and JavaScript ``camelCase`` styles.

**Highcharts for Python** vs Alternatives
==============================================

For a discussion of **Highcharts for Python** in comparison to alternatives, please see
the **COMPLETE DOCUMENTATION:** http://core-docs.highchartspython.com/en/latest/index.html

----------------

**************************************
Highcharts for Python Components
**************************************

Use the following links to learn more about each of the tools in the **Highcharts for Python** Toolkit:

  * `Highcharts Core for Python <https://github.com/highcharts-for-python/highcharts-core>`__
  * `Highcharts Stock for Python <https://github.com/highcharts-for-python/highcharts-stock>`__
  * `Highcharts Maps for Python <https://github.com/highcharts-for-python/highcharts-maps>`__
  * `Highcharts Gantt for Python <https://github.com/highcharts-for-python/highcharts-gantt>`__

---------------------------

***************************
Getting Help / Support
***************************

The **Highcharts for Python Toolkit** comes with all of the great support that you are used to from working with the 
Highcharts JavaScript libraries. When you license the toolkit, you are welcome to use any of the following channels 
to get help using the toolkit. In particular, you can:

  * Use the `Highcharts Forums <https://highcharts.com/forum>`__
  * Use `Stack Overflow <https://stackoverflow.com/questions/tagged/highcharts-for-python>`__ with the 
    ``highcharts-for-python`` tag
  * `Report bugs or request features <https://github.com/highcharts-for-python/highcharts-core/issues>`__  in one of
    our Github repositories
  * `File a support ticket <https://www.highchartspython.com/get-help>`__ with us, or
  * `Schedule a live chat or video call <https://www.highchartspython.com/get-help>`__ with us

**FOR MORE INFORMATION:** https://www.highchartspython.com/get-help

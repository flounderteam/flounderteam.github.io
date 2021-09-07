.. Packaging Scientific Python documentation master file, created by
   sphinx-quickstart on Thu Jun 28 12:35:56 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Algorithmic Trading Research Platform
======================================

The platform is built around the `Zipline <https://flounderteam.github.io/refs/zipline/>`_ framework
enabling to connect multiple data sources with multiple analytical approaches for conducting diverse
studies. The figure provides a conceptual outline of its architecture.

.. image:: images/platform.png
    :width: 650

Within this framework, the Pipeline is a custom collection of cross-sectional
trailing-window tasks (Factors, Classifiers, and Filters) propagated by Pipeline
Engine through the backtest interval. The Zipline data layer is organized
as a collection of named data bundles associated with different data sets.
The `Flounder-Sharadar <https://flounderteam.github.io/fsharadar/>`_ extension provides
consolidated interface for ingesting and accessing bundles produced from the
`Sharadar <https://www.quandl.com/publishers/SHARADAR>`_ data sets with daily prices,
fundamentals, and metadata of US assets. 

.. toctree::
   :maxdepth: 1

   install
   running
   contactus


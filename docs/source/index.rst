PyDAX Documentation
===================

PyDAX is a simple Python API for downloading and loading datasets from IBM's `Data Asset Exchange`_.

.. _Data Asset Exchange: https://developer.ibm.com/exchanges/data/

.. toctree::
   :caption: User Guide
   :glob:
   :maxdepth: 1

   user_guide/*

API References
--------------

.. autosummary::
   :caption: API References
   :toctree: api-references
   :template: our-module.rst

   pydax
   pydax.dataset
   pydax.exceptions
   pydax.schema

Loaders
~~~~~~~

.. autosummary::
   :caption: API References (Loaders)
   :toctree: api-references
   :template: our-module.rst

   pydax.loaders
   pydax.loaders.table
   pydax.loaders.text


.. toctree::
   :caption: Miscellaneous
   :glob:
   :maxdepth: 1

   miscellaneous/*

Indices and Search
==================

* :ref:`genindex`
* :ref:`search`

.. Waste Detection System documentation master file, created by
   sphinx-quickstart on Sun Dec 11 16:12:54 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Waste Detection System Documentation
==================================================

This compilation of documentation corresponds to  the `the waste detection system package <https://github.com/plazarotello/waste-detection-system>`_. 
For installation, please note that the package has been tested in Windows 10; since it relies on conda and pip for dependency management and both
systems are platform independent, i should be easy to port the installation dependencies to Unix or other Windows versions.

.. warning::
   The installation script uses ``conda``

#. Download the repository from `here <https://github.com/plazarotello/waste-detection-system>`_.
#. Open a powershell or bash command line in the directory's root.
#. Execute the dependencies' installation script found on the ``scripts`` folder: 

   * For Windows: execute ``.\scripts\setup.ps1``

   * For Unix: execute ``. ./scripts/setup.sh``

Now you should have a ``waste-detector`` conda environment with all dependencies installed.


Code documentation
==================

.. toctree::
   :maxdepth: 2
   :titlesonly:

   Waste Detection System <waste_detection_system>
   Entry point of the module <waste_detection_system-entry_point>
   Available models <waste_detection_system-models>
   Training scripts <waste_detection_system-training>
   Utilities <waste_detection_system-utils>
   Constants <waste_detection_system-constants>



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

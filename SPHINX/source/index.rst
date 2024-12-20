.. CMAQ_Documentation documentation master file, created by
   sphinx-quickstart on Wed Dec 11 14:55:46 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

CMAQ: The Community Multiscale Air Quality Modeling System
==========================================================


**CMAQ:** an active open-source development project of the U.S. EPA that consists of a suite of programs for conducting air quality model simulations. CMAQ combines current knowledge in atmospheric science and air quality modeling, multi-processor computing techniques, and an open source framework to deliver fast, technically sound estimates of ozone, particulates, toxics and acid deposition.

.. note::

        Not the official CMAQ User's Guide

This website contains documentation for the `Community Multiscale Air Quality (CMAQ) <https://epa.gov/cmaq>`_ modeling system. While documentation is packaged with the code when it is downloaded or cloned, users are encouraged to go `online <https://github.com/USEPA/CMAQ/tree/main/DOCS>`_ to view the latest version. 



.. grid:: 1 1 2 2
        :gutter: 1 1 1 1

        .. grid-item-card::
            :text-align: center
        
            **User's guide**
            ^^^

            Instructions on how to set up and run the model and information on CMAQ's different science options and instrumented versions..

            +++

            .. button-ref:: <Users_Guide/README>
                :click-parent:
                
                To the User's Guide

        .. grid-item-card:: **Tutorials**

                Included with the User's Guide, a series of short tutorials provide practical examples of how to set up and run CMAQ, exercise different features in the software, and better understand the software system.

                :doc:`Tutorials </Users_Guide/Tutorials/README.md>`
                
        
        .. grid-item-card:: **Developer's Guide**

                A guide to version control practices and expectations adopted by the CMAQ development team and enforced on itself and any other collaborators who wish to contribute code.

                :doc:`Developer's Guide </Developers_Guide/CMAQ_Dev_Guide.md>`


        .. grid-item-card:: **Release Notes**

                Technical notes on the new features and science in this release of CMAQ are available on the CMAQ Wiki.

                `Release Notes <https://github.com/USEPA/CMAQ/wiki/CMAQ-Release-Notes>`_ 




.. toctree::
   :maxdepth: 1
   :hidden:

   Documentation  <./Docs_README>
   User's Guide <Users_Guide/README>
   Tutorials <Users_Guide/Tutorials/README>
   Developer's Guide <Developers_Guide/CMAQ_Dev_Guide>



SCANOSS Documentation
=====================

Welcome to the SCANOSS Documentation Hub! This page serves as your central resource for exploring the various open-source tools and features available within the SCANOSS platform. Whether you're getting started or looking for advanced functionalities, you'll find comprehensive guides and resources here.


Platform Overview
-----------------

SCANOSS is a versatile platform designed to help you manage and analyze the open-source components within your software projects. It offers a suite of free and open-source tools for tasks such as generating SBOMs (software bill of materials), scanning for dependencies, assesing vulnerabilities, license compliance, and more.

.. note::
   Every SCANOSS tool is published to our GitHub Organization page, you can find the link on the menu to the left.

Available Tools
---------------

Explore the various open-source tools available within the SCANOSS platform:

- **SCANOSS Engine:** The central tool for scanning and analyzing software components, providing insights into licenses, vulnerabilities, and compliance
- **SBOM Workbench:** The SBOM Workbench is a graphical user interface to scan and audit source code using SCANOSS API
- **CLIs and Packages:** We released packages in different programming languages (Python, Java, Javascript, etc) that can be run from the command line, or consume from another script
- **APIs:** We release multiple APIs to query a knowledge base (for example, `OSSKB <https://www.softwaretransparency.org/osskb>`_)

What You'll Find Here
---------------------

In this hub, you'll find a range of resources to help you get the most out of each SCANOSS tool:

- **User Guides:** Step-by-step instructions to help you set up and begin using the various SCANOSS tools
- **API Documentation:** Comprehensive reference material for integrating SCANOSS tools with your applications and workflows
- **Best Practices:** Tips and strategies for optimizing your use of SCANOSS tools to ensure maximum efficiency and security
- **FAQs and Troubleshooting:** Solutions to common issues and answers to frequently asked questions

Navigation
----------

Use the menu on the left to explore different sections of the documentation. Each section is organized by tool and topic, providing you with targeted information based on your needs.


.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Contents

   tools/engine.rst
   tools/workbench.rst
   tools/cli.rst
   tools/api.rst

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Links

   SCANOSS Website <https://www.scanoss.com/>
   GitHub <https://github.com/scanoss>
   Software transparency foundation <https://www.softwaretransparency.org/>
=====================================
Product Account Multi-Company Default
=====================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:829354ccfa7140cb2a84be15e017e5e0ed314e0c3bbb90065caa74abd01507fd
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Alpha-red.png
    :target: https://odoo-community.org/page/development-status
    :alt: Alpha
.. |badge2| image:: https://img.shields.io/badge/licence-LGPL--3-blue.png
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fmulti--company-lightgray.png?logo=github
    :target: https://github.com/OCA/multi-company/tree/16.0/product_account_multicompany_default
    :alt: OCA/multi-company
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/multi-company-16-0/multi-company-16-0-product_account_multicompany_default
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/multi-company&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module extends the functionality of products and accounting to allow you
to propagate multi-company product template and product category accounts from the current company to all
other companies where you have access rights.

.. IMPORTANT::
   This is an alpha version, the data model and design can change at any time without warning.
   Only for development or testing purpose, do not use in production.
   `More details on development status <https://odoo-community.org/page/development-status>`_

**Table of contents**

.. contents::
   :local:

Configuration
=============

To configure this module, you need to:

#. Install some module that lets you manage products, such as sale, purchase...
   (if not already installed).

Usage
=====

To use this module, you need to:

#. Go to a product's form view. It can be the product template or the variant.
#. Enter the "Accounting" tab.
#. Click on "Propagate expense/income account to other companies".

Known issues / Roadmap
======================

Since this module propagates product accounts based on the account code, it
should only be used in a database where all companies belong to the same country.

We could add a wizard that allows the user to select multiple products and propagate
their accounts to multiple companies, in mass. This would improve the usability and fix
the issue on multi-country installations. Example:

.. figure:: https://raw.githubusercontent.com/OCA/multi-company/16.0/product_account_multicompany_default/static/description/wizard-mockup.drawio.png
   :alt: Wizard mockup

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/multi-company/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/multi-company/issues/new?body=module:%20product_account_multicompany_default%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Moduon

Contributors
~~~~~~~~~~~~

* Jairo Llopis (`Moduon <https://www.moduon.team/>`__)
* Telmo Santos <telmo.santos@camptocamp.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-yajo| image:: https://github.com/yajo.png?size=40px
    :target: https://github.com/yajo
    :alt: yajo

Current `maintainer <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-yajo| 

This module is part of the `OCA/multi-company <https://github.com/OCA/multi-company/tree/16.0/product_account_multicompany_default>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.

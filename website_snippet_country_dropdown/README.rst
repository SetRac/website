[![Build Status](https://travis-ci.org/zeroincombenze/website.svg?branch=8.0)](https://travis-ci.org/zeroincombenze/website)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/website/badge.svg?branch=8.0)](https://coveralls.io/github/zeroincombenze/website?branch=8.0)
[![codecov](https://codecov.io/gh/zeroincombenze/website/branch/8.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/website/branch/8.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-8.svg)](https://github.com/OCA/website/tree/8.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-8.svg)](http://erp8.zeroincombenze.it)


[![en](https://github.com/zeroincombenze/grymb/blob/master/flags/en_US.png)](https://www.facebook.com/groups/openerp.italia/)

.. image:: https://img.shields.io/badge/licence-LGPL--3-blue.svg
================================================================
   :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
   :alt: License: LGPL-3

Snippet's dropdown country code

This module adds a snippet with a dropdown and an input text field, is a base
for be inherited by others modules into an HTML form.

This can be inserted into form elements.

Installation
------------








Configuration
-------------








Usage
-----

-----

-----

-----

-----

-----

-----

-----

=====

To extend this template you need to inherit *country_dropdown* template and to
add you personal code.

The template have three input text:

#. no_country_field: Field without code country.
#. country_code_field: Field with only country code (read only)
#. complete_field: Field with the previous two joined (hidden)

The name of the complete field is customizable when user insert the snippet
into a form element with the website editor.

Development

You can call the reusable Qweb template called
``website_snippet_country_dropdown.country_dropdown`` in your views to add a
sensible country-combined field, ideal for *VATs*.

The default country will be the first match among:

#. Extract it from the ``default_country`` variable.
#. Extract it from the first 2 letters of the ``default_value`` variable.
#. The current user's country.
#. The current website's company's country.
#. The first country in the list.

You can view an example in
https://github.com/OCA/e-commerce/tree/8.0/website_sale_checkout_country_vat.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/186/8.0

Known issues / Roadmap
----------------------









* Add tests.

Bug Tracker
-----------









Bugs are tracked on `GitHub Issues
<https://github.com/OCA/website/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed `feedback
<https://github.com/OCA/
website/issues/new?body=module:%20
website_snippet_country_dropdown%0Aversion:%20
8.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Credits
-------









Images

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.

[![Odoo Italia Associazione]]








### Contributors









* Sergio Teruel <sergio.teruel@tecnativa.com>

### Funders

### Maintainer
















.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit http://odoo-community.org.

[//]: # (copyright)

----

**Odoo** is a trademark of [Odoo S.A.](https://www.odoo.com/) (formerly OpenERP, formerly TinyERP)

**OCA**, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

**zeroincombenze®** is a trademark of [SHS-AV s.r.l.](http://www.shs-av.com/)
which distributes and promotes **Odoo** ready-to-use on its own cloud infrastructure.
[Zeroincombenze® distribution](http://wiki.zeroincombenze.org/en/Odoo)
is mainly designed for Italian law and markeplace.
Everytime, every Odoo DB and customized code can be deployed on local server too.

[//]: # (end copyright)

[//]: # (addons)

[//]: # (end addons)

[![chat with us](https://www.shs-av.com/wp-content/chat_with_us.gif)](https://tawk.to/85d4f6e06e68dd4e358797643fe5ee67540e408b)

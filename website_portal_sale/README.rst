[![Build Status](https://travis-ci.org/zeroincombenze/website.svg?branch=8.0)](https://travis-ci.org/zeroincombenze/website)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/website/badge.svg?branch=8.0)](https://coveralls.io/github/zeroincombenze/website?branch=8.0)
[![codecov](https://codecov.io/gh/zeroincombenze/website/branch/8.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/website/branch/8.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-8.svg)](https://github.com/OCA/website/tree/8.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/man/SD)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-8.svg)](http://erp8.zeroincombenze.it)


[![en](https://github.com/zeroincombenze/grymb/blob/master/flags/en_US.png)](https://www.facebook.com/groups/openerp.italia/)

.. image:: https://img.shields.io/badge/licence-LGPL--3-blue.svg
================================================================
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3


Website Portal for Sales

Backport (with adjustments) of the ``website_portal_sale`` module of Odoo 9.

This module add the user's sales documents in the frontend portal.
Customers will be able to see the list and state of their quotations, sales
and invoices.

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

=====

Go to Sales > Customer > More options > Portal Access Management and invite it
to access at portal.

When a customer clicked to his name > my account then he can see his orders if
hi is follower of them.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/186/8.0

For further information, please visit:

* https://www.odoo.com/forum/help-1

Known Issues / Roadmap

* In v9, the field ``validity_date`` of the sale order has been moved from the
  ``website_quote`` module to the base ``sale`` module, therefore the module
  references it without problem as the ``sale`` module is a dependency of this
  one.
  For version 8 the validity_date on the portal has been removed completely at
  the moment. Instead, we should make a conditional template that shows the field
  if the ``website_quote`` module is installed.
* Tests

Known issues / Roadmap
----------------------





Bug Tracker
-----------






Bugs are tracked on `GitHub Issues <https://github.com/OCA/website/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed feedback
`here <https://github.com/OCA/website/issues/new?body=module:%20website_portal_sale%0Aversion:%208.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Credits
-------






[![Odoo Italia Associazione]]





### Contributors






* Odoo SA <https://www.odoo.com>
* Leonardo Donelli @ MONK Software <donelli@webmonks.it>
* Rafael Blasco <rafabn@antiun.com>
* Sergio Teruel <sergio@incaser.es>

**This module is a backport from Odoo SA and as such, it is not included in
the OCA CLA. That means we do not have a copy of the copyright on it like
all other OCA modules.**

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

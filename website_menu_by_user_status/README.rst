[![Build Status](https://travis-ci.org/zeroincombenze/website.svg?branch=10.0)](https://travis-ci.org/zeroincombenze/website)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/website/badge.svg?branch=10.0)](https://coveralls.io/github/zeroincombenze/website?branch=10.0)
[![codecov](https://codecov.io/gh/zeroincombenze/website/branch/10.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/website/branch/10.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-10.svg)](https://github.com/OCA/website/tree/10.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-10.svg)](http://wiki.zeroincombenze.org/en/Odoo/10.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-10.svg)](http://wiki.zeroincombenze.org/en/Odoo/10.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-10.svg)](http://erp10.zeroincombenze.it)


[![en](https://github.com/zeroincombenze/grymb/blob/master/flags/en_US.png)](https://www.facebook.com/groups/openerp.italia/)

Website Menu By User Status
===========================

The module manages display website menu entries, depending if the user is
logged or not.
The selection of the display status can be chosen logged and/or not.
Extends features and view of website.menu model.

Website.menu list view can be found at:
Settings > Configuration > Website Settings > Configure Website menus

The module inherit from website.menu to add 2 booleans fields, user_logged
and user_not_logged.
On top of that, website.layout template is extended to include a condition
that drive if the menu is built or not.
It has been choose to not only hide the menu to avoid to easily get around
by editing the html DOM.

Installation
------------










Configuration
-------------










Usage
-----














Known issues / Roadmap
----------------------










Bug Tracker
-----------










Credits
-------




















### Contributors










* Bruno Joliveau <bruno.joliveau@savoirfairelinux.com>
* Jordi Riera <jordi.riera@savoirfairelinux.com>

More information
Module developed and tested with Odoo version 8.0
For questions, please contact our support services
<support@savoirfairelinux.com>

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

sa-communication-tools
======================

[![Build Status](https://travis-ci.org/softasap/sa-communication-tools.svg?branch=master)](https://travis-ci.org/softasap/sa-communication-tools)

Installs popular communication tools hipchat (modern client - hipchat4), slack, viber, skype


Example of use:

<pre>

     - {
         role: "sa-communication-tools",
         skypeforlinux_version: 1.10.0.1,
         option_skype: false,
         option_skype_rec: false,
         option_viber: true,
         option_slack: true,
         option_hipchat: false,
         option_hipchat4: true,         
         option_skype_linux: true,
         option_telegram: true
       }

</pre>


Note: re skypeforlinux_version  - existing repo holds only two recent versions, and now historic one. Also there is no "latest" deb to install most recent version only.
This would require you to check and set actual version for skypeforlinux_version



# Change notes

1.1.0 Introduced support for telegram and skype alpha for linux according to feature requests


Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter channel [Gitter] (https://gitter.im/softasap)

sa-communication-tools
======================

[![Build Status](https://travis-ci.org/softasap/sa-communication-tools.svg?branch=master)](https://travis-ci.org/softasap/sa-communication-tools)

Installs popular communication tools hipchat, slack, viber, skype


Example of use:

<pre>

     - {
         role: "sa-communication-tools",
         skypeforlinux_version: 1.10.0.1,
         option_skype: false,
         option_skype_rec: false,
         option_viber: true,
         option_slack: true,
         option_hipchat: true,
         option_skype_linux: true,
         option_telegram: true
       }

</pre>


Note: re skypeforlinux_version  - existing repo holds only two recent versions, and now historic one. Also there is no "latest" deb to install most recent version only.
This would require you to check and set actual version for skypeforlinux_version


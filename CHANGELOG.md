commit 16ebca5e87584a9bbf8db718a8de6b72d9f6e0c9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Mar 13 01:06:09 2020 -0400

    Minor tweaks from testing

commit bc6848c9e69bcfdcc133bf5bb3a32b560362fae8
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Mar 13 01:05:26 2020 -0400

    Fixed RDP package for Ubuntu 18.04

commit 9309992d9eb35d6464d93359d30270b85ac33092
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Mar 13 01:04:44 2020 -0400

    Added: Handler to kill guacd before restart
    
    Restarting guacd was causing issues with hanging and failing

commit b2fcbc404562433b4008c3bd4792110c8e321fe1
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Feb 21 16:06:34 2020 -0500

    Disabled Fedora testing
    
    - Fedora is failing. Will review this at a later time.

commit 85359a995b5b65c71c0be403354cc48956db74ad
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Feb 21 15:43:00 2020 -0500

    Disabled Debian 10 testing
    
    - Looks like there is an issue with Debian 10 working for now

commit bf4a58ed254c16dcb3afeac062196a858582841a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Feb 21 14:59:56 2020 -0500

    Disabled Debian 9 testing
    
    - Debian 9 fails because of Tomcat 9 pre-req

commit 1ea8bfcbe964337fc9d6158bab1f08762b9f2a71
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Feb 21 14:41:15 2020 -0500

    Changed Molecule scenarios, tests, etc.

commit 3af9540273c48e8150ed8aad3b7f594878269d7a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Feb 21 14:41:05 2020 -0500

    Updated files, etc. after new structure

commit 18bce9a45ba0bdc897c23cccd520d2e86349f105
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Feb 18 17:29:30 2020 -0500

    Fixed RedHat service name

commit f8ffadc697bed3ba851230f4420b765f9cd2525d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Feb 18 17:29:21 2020 -0500

    Disabled failing Debian 10 for now

commit 93a9189c86b6a56384d234864ccf739e8c72a50f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Feb 18 16:24:23 2020 -0500

    Added Ansible linting issues

commit 933f749a43ad64b699166ccbe5e8788656cb64f9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Feb 18 16:22:03 2020 -0500

    New files, etc. based on Cookiecutter template

commit 559b3e71e969354c8da5d177c8d5f9d50efe1c7b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Feb 18 16:21:42 2020 -0500

    Cleanup based on changes in Cookiecutter template

commit 74fb9d53d525c7840ddabdf5976ac69392088f51
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Feb 18 16:20:37 2020 -0500

    Updated tasks based on new Molecule testing, etc.
    
    - There were some tasks, vars, etc. which needed to be addressed based
    on Molecule testing. These changes address these issues.

commit 836c112f2c1ec9a03226361c5c4bceac6e3fdca3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Feb 18 14:53:13 2020 -0500

    Removed old tests, etc.

commit 8ab0f53b0915fa272afda163e8009fb0555c5995
Author: juju4 <juju4@users.noreply.github.com>
Date:   Sun Jan 19 21:02:26 2020 -0500

    get_url: add retries

commit 495e26e9b318963aacea47d0b397885421b60468
Author: juju4 <juju4@users.noreply.github.com>
Date:   Sat Jan 11 14:42:57 2020 -0500

    update to 1.0.0

commit 841d52531e37bc9dfbe2046cbdffe6513492ec9a
Author: juju4 <juju4@users.noreply.github.com>
Date:   Sat Jan 11 14:42:40 2020 -0500

    guacamole_basic_user_mapping, guacd-port options

commit ff11b516b2a0975fce084aee798de064e23c6acc
Author: juju4 <juju4@users.noreply.github.com>
Date:   Sat Jan 11 14:41:52 2020 -0500

    add rdp ignore-cert option

commit 4ac5ed1d6284052936bb9fbf65ae427bb3f10d3b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Dec 31 15:35:44 2018 -0500

    Added VNC connections

commit 0c35573b8dbd518114d30f94b9661809690663eb
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Dec 23 01:13:13 2018 -0500

    Cleaned up formatting of code

commit 280c1b81ceda1333d3bcb10a58de684eda75ba8c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Dec 22 00:48:29 2018 -0500

    Fixing idempotency issue with client permissions

commit 6df1db71ee474b5c749507079b7cface16a21328
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Dec 22 00:08:07 2018 -0500

    First working commit of MySQL Auth functionality.

commit 3affba5a39e543c1af052f0cc7918d910180345d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Dec 21 15:53:49 2018 -0500

    Disabled Ubuntu 18.04 as there are issues with building Guacamole server

commit f36dce5e5ca583be7967fd377d80ea5834d08147
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Dec 21 15:53:29 2018 -0500

    Updated Galaxy info

commit b4c3f1bf7d235992f3fc710ee77317fb7ba28b92
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Dec 21 15:38:12 2018 -0500

    Complete refactoring of role
    
    This was a very much needed refactoring. Previously Ubuntu did not work
    at all, whereas CentOS worked fine. Also, implemented Travis CI testing.

commit 9f3da01bb1d36717ff25e5394a47d4256aaef07e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Nov 28 14:26:06 2017 -0500

    Create LICENSE

commit 4ada7108b8a5768d7c4711728dfd8c2b9bc8c9bd
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Nov 28 14:24:43 2017 -0500

    first commit

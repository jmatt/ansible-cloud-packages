ansible-cloud-packages
======================

[![Build Status](https://travis-ci.org/jmatt/ansible-cloud-packages.svg?branch=master)](https://travis-ci.org/jmatt/ansible-cloud-packages)

Install packages for cloud deployment for LSST SQuaRE infrastructure.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lsst-sqre.cloud-packages }

License
-------

See the [LICENSE file](https://github.com/lsst-sqre/ansible-cloud-packages/blob/master/LICENSE).

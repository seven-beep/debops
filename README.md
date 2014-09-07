## nodejs

[![Travis CI](https://secure.travis-ci.org/debops/ansible-nodejs.png)](http://travis-ci.org/debops/ansible-nodejs) [![test-suite](http://img.shields.io/badge/test--suite-ansible--nodejs-blue.svg)](https://github.com/debops/test-suite/tree/master/ansible-nodejs/) [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.nodejs-660198.svg)](https://galaxy.ansible.com/list#/roles/1581)[![Platforms](http://img.shields.io/badge/platforms-debian%20|%20ubuntu-lightgrey.svg)](#)

This role can be used as a dependency for other roles to provide NodeJS and
npm support.

At the moment, on Debian Wheezy a `nodejs` package from `wheezy-backports`
is installed, and `npm` command is installed from upstream using a script;
this will be changed in the future to install `npm` package as a backported
Debian Jessie version.


### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.nodejs






### Role variables

List of default variables available in the inventory:

    ---
    
    # List of packags to install
    nodejs_packages: [ 'nodejs', 'nodejs-legacy' ]




### Authors and license

`nodejs` role was written by:

- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-(gpl-3))

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).

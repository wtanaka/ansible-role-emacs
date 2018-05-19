[![Build Status](https://travis-ci.org/wtanaka/ansible-role-emacs.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-emacs)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-emacs.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-emacs)

wtanaka.emacs
=============

Installs emacs

Example Playbook
----------------

    - hosts: servers
      roles:
         - wtanaka.emacs

### `emacs_should_shortcircuit`

Default: True

When True, this role short-circuits itself if a "emacs" is already in the path


License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/

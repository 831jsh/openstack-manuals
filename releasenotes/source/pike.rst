============
Pike release
============

* As of the Pike release, the complete documentation suite that resided within
  the openstack-manuals repository has been reworked, and the content of the
  following guides has been moved to the project team repositories:

  - Installation Guide
  - Administration Guide
  - End User Guide
  - Command-Line (CLI) Reference
  - Configuration Reference

* All of the documentation builds (except for release notes and the
  api-ref) have been combined so that each
  repository has a single ``doc/source`` directory, a single
  sphinx ``conf.py``, and a single job for building and
  publishing the content including developer, contributor,
  and user documentation.

* The Operations Guide is in the process of being migrated to the
  OpenStack wiki. It is unavailable on docs.openstack.org from Pike.

Contributor Guide
~~~~~~~~~~~~~~~~~

* Added content about the new release process.
* Updated guide to be relevant for updated openstack-manuals.
* General bug fixes and updates.

Security Guide
~~~~~~~~~~~~~~

* Updated Keystone Checklists
* Rework of 'node hardening' section
* Various fixes such as grammar and incorrect hyperlinks

Training Labs
~~~~~~~~~~~~~

* Support for the new OpenStack release will be available shortly
  after the release of Pike.
* Various bug fixes and minor improvements in the host scripts.

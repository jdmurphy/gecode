gecode cookbook CHANGELOG
=========================
This file is used to list changes made in each version of the gecode cookbook.

v2.1.2 (2015-10-20)
-------------------
* Added source_url and issues_url to the metadata
* Updated the Berksfile to 3.x format
* Updated the gitignore file
* Test on the latest Freebsd boxes in Test Kitchen
* Added chefignore file
* Added Chef standard rubocop config
* Updated Travis CI testing to use the ChefDK for up to date deps
* Updated Gemfile with the latest testing deps
* Updated testing and contributing docs
* Added maintainers.md and maintainers.toml files
* Added travis and cookbook version badges to the readme
* Resolved Rubocop warnings
* Added a .foodcritic file to exclude warnings

v2.1.0
------
- Updating to use yum ~> 3.0
- Fixing up style for rubocop
- Updating test-kitchen harness

v2.0.8
------
fixing metadata version error. locking to 3.0"

v2.0.6
------
Updating CHANGELOG for stove compat

v2.0.2
------
### Bug
- [COOK-2959]: gecode cookbook has foodcritic failure

v2.0.0
------
* [COOK-1868] - use `node['platform_family']` to handle multiple
  platforms better

v1.3.0
------
* [COOK-1713] - switch to gecode package in Fedora, EPEL >= 6

v1.2.0
------
* [COOK-663] - upgrade libgecode-dev package
* [COOK-778] - update ld.so.conf

1.0.2
-----
* split default recipe into source and package recipe (follows pattern of other cookbooks)
* externalize source installation metadata into attributes
* verify mac os x platform support

1.0.0
-----
* [COOK-538] fix gecode install on newer ubuntu and debian releases
* [COOK-680] don't rebuild gecode if it is already installed

0.99.0
------
* initial release

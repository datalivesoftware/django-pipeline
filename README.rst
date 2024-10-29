
History of this Datalive Fork of django-pipeline
================

5.0.2
-----

Note: many of datalive's projects have reinstated django-pipeline in favour of this fork, as it has py3.12 and django 5+ support, among other maintenance.

* Yank 5.0.1 as bugfix was incorrectly generating blank files
* Make simpler change to use import_string instead of get_storage_class as per original django code (see https://github.com/django/django/blob/4.2.16/django/core/files/storage/__init__.py)

5.0.1
-----

* Fix for default_storage

5.0.0
-----

* Make Django 5.0 compatible by using the STORAGES setting and removing references to get_storage_class.

3.0.0
-----

* Make Django 3.2 compatible by removing reference to CachedStaticFilesStorage and replacing it with ManifestStaticFilesStorage.  Make sure you have fully tested this works.

2.0.1
-----

* Fix for get_modified_time(infile)
* Fix some imports

2.0.0
-----

* Package up all forked changes for datalivepypi

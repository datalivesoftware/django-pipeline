
History of this Datalive Fork of django-pipeline
================

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

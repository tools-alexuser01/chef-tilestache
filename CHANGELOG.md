tilestache CHANGELOG
===================

0.17.4
------
- bump version of mapbox_vector_tile to 0.0.6

0.17.3
------
- bump version of mapbox_vector_tile to 0.0.5

0.17.2
------
- bump version of mapbox_vector_tile to 0.0.3

0.17.1
------
- update pip requirements generation strategy
- upgrade packages with pip when installing
- add memcache to pip requirements
- add mapbox-vector-tile to pip requirements

0.17.0
------
- gunicorn installation is optional
- use python-pil apt package instead of python image package
- new pip_requirements install method
- remove running apache cookbook

0.16.4
------
- fix the tilestache config template restart resources

0.16.3
------
- make svwait configurable
- increase default wait to 180 seconds

0.16.2
------
- call runit_service explicitly to restart when using runit

0.16.1
------
- don't run a finish script with runit

0.16.0
------
- upgrade to gunicorn 19.1.0
- allow setting of tornado version, default 4.0.1
- install tornado from pip

0.15.3
------
- override default sv_timeout

0.15.2
------
- clean up recipe logic

0.15.1
------
- upgrade default version to 1.49.11

0.15.0
------
- default to tornado rather than sync
- clean up specs
- clean up gunicorn recipe

0.14.1
------
- also install python-pylibmc, as there are outstanding pull requests to support it in tilestache

0.14.0
------
- stable

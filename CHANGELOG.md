## 0.8.0

- Fix for support Mongoid 5.x, and only work on `Mongoid >= 5.0.0`,
  If you want use for Mongoid 4.x, please use 0.7.0.

## 0.7.0

* Add sequence cache config to allow you generate a range ids, and reduce MongoDB write.

## 0.6.5

* MongoDB Replicate Set support. by @junwchina

## 0.6.4

* Rails 4.1.0 support.

## 0.6.3

* Fix _id overwriting warnning with Mongoid 4.0+;

## 0.6.2

* Mongoid `create_indexes` and `remove_indexes` Rake task bug fixed, this bug will appear in Mongoid 3.1.0+.
* This version is depending Mongoid 3.1.0+.

## 0.6.1

* Fix id some time will get a float value in JRuby.

## 0.6.0

* Support for Mongoid 3.0.0 - 4.0.0+;
* Test work under Rails 4;

## 0.5.1

* Support for Mongoid 3.1.x

## 0.5.0

* Support for Mongoid 3.0.x

## 0.4.0

* Support for Mongoid 2.4.x

## 0.3.1

* Support for Mongoid 2.3.x

## 0.2.2

* Support for Mongoid 2.2.x

# Changes

## v0.9.0 - 23/1/23

* Full fork with added support for node-mapnik v4.x.x
* Add a hack to work around mapnik-reference incompatibility 

## v0.8.2 - 7/12/18

* Delegate `getInfo()` to `tilelive-bridge` to prevent data leakage

## v0.8.1 - 7/10/18

* Update to match new `carto.Renderer.render()` return signature

## v0.8.0 - 6/28/18

* Upgrade `@mapbox/tilelive-bridge` to `^3.0.0`

## v0.7.0 - 5/2/18

* Support YAML input in place of a URI (or as a `yaml` property on the provided
  URI object)
* Remove deprecated `layer.name` property

## v0.6.1 - 6/14/17

* Fix dependency `require`s

## v0.6.0 - 6/13/17

* Update dependencies

## v0.5.0 - 5/27/16

* Update `tilelive-bridge` dependency to support MVT v2 spec.

## v0.4.3 - 1/18/16

* Fix `getInfo` callback

## v0.4.2 - 10/27/15

* Eliminate unnecessary (and potentially expensive) sorting of object keys to
  be written into Mapnik XML.

## v0.4.1 - 10/27/15

* Catch errors from `normalize()`

## v0.4.0 - 8/17/15

* Use newest `mapnik-reference` (for compatibility w/ mapnik 3.x)

## v0.3.0 - 1/15/15

* Declare a peer dependency on `mapnik`

## v0.2.0 - 1/15/15

* Fix use of `mapnik-reference`
* Update dependencies
* Use synchronous `carto.render()`

## v0.1.3 - 1/15/15

* Relax `mapnik` dependency to work with 3.x.x
* Update `mapnik-reference` dependency

## v0.1.2 - 7/3/14

* Handle relative paths in datasource files properly
* Partial sync with tm2

## v0.1.1 - 6/30/14

* Don't crash when a layer doesn't have an extent set (JesseCrocker)

## v0.1.0 - 4/28/14

* Initial version

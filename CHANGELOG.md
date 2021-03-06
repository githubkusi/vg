Changelog
=========

## 1.1.0 (May 13, 2019)

- Add `vg.almost_unit_length`
- Add `vg.within`

## 1.0.0 (Apr 4, 2019)

- BREAKING CHANGE: Rename `vg.proj()` -> `vg.project()`.
- BREAKING CHANGE: Rename `vg.sproj()` -> `vg.scalar_projection()`.
- BREAKING CHANGE: Move matrix functions into namespace.
- BREAKING CHANGE: Give second argument to `vg.apex()` a better name
- Add `vg.almost_equal()`.
- Improve documentation.

## 0.6.0 (Apr 3, 2019)

- Add `vg.shape.check()` and `vg.shape.check_value()`

## 0.5.2 (Mar 28, 2019)

- Again, fix concurrent install with numpy by avoiding numpy import during install.

## 0.5.1 (Mar 28, 2019)

- Fix concurrent install with numpy by avoiding numpy import during install.

## 0.5.0 (Mar 28, 2019)

- Add `vg.apex()` and `vg.farthest()`
- Fix documentation typos.
- Update dev dependencies.


## 0.4.0 (Jan 17, 2019)

- Add `vg.perpendicular()` for computing the vector perpendicular to two
  others.
- Add `vg.rotate()` for rotating a point or vector some number of degrees
  (or radians) around an axis.
- Add "before and after" examples to the docs.
- **100% code coverage.**

## 0.3.0 (Nov 16, 2018)

- Add principal-component-analysis functions `principal_components()` and
  `major_axis()`.


## 0.2.0 (Oct 5, 2018)

- Vectorize `angle()` and `unsigned_angle()` and improve documentation and
  test coverage.
- Test the return type for `magnitude()` and improve documentation.
- Present documentation on a single page.
- Other doc improvements.


## 0.1.0 (Oct 2, 2018)

Initial release.

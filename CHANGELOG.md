# Change Log

## [Unreleased]


## [0.5.1]
### Added
- Support watchOS 64-bit.

## [0.5.0]
### Changed
- Upgrade to Kotlin 1.5.0.
- Upgrade to kotlinx.coroutines 1.5.0.

## [0.5.0-rc1]
### Changed
- Upgrade to Kotlin 1.5.0.
- Upgrade to kotlinx.coroutines 1.5.0-RC.

## [0.4.1]
### Changed
- Upgrade to kotlinx.coroutines 1.4.3.
- Removed requirement to opt-in to `@ExperimentalCoroutinesApi`.

## [0.4.0]
### Changed
- Upgrade to Kotlin 1.4.30.

## [0.3.0]
### Added
- `cancelAndConsumeRemainingEvents()` cancels the `Flow` and returns any unconsumed events which were already received.
- `expectEvent()` waits for an event (item, complete, or error) and returns it as a sealed type `Event`.

## [0.2.1]
### Added
- Support Javascript IR backend.

## [0.2.0] - 2020-08-17
### Changed
- Upgrade to Kotlin 1.4.

## [0.1.1] - 2020-08-03
### Fixed
- Use the [`Unconfined`](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines/-dispatchers/-unconfined.html) dispatcher for the internal flow collection coroutine which should eliminate the need to use `yield()` in tests.

## [0.1.0] - 2020-08-03

Initial release


[Unreleased]: https://github.com/cashapp/turbine/compare/0.5.1...HEAD
[0.5.1]: https://github.com/cashapp/turbine/releases/tag/0.5.1
[0.5.0]: https://github.com/cashapp/turbine/releases/tag/0.5.0
[0.5.0-rc1]: https://github.com/cashapp/turbine/releases/tag/0.5.0-rc1
[0.4.1]: https://github.com/cashapp/turbine/releases/tag/0.4.1
[0.4.0]: https://github.com/cashapp/turbine/releases/tag/0.4.0
[0.3.0]: https://github.com/cashapp/turbine/releases/tag/0.3.0
[0.2.1]: https://github.com/cashapp/turbine/releases/tag/0.2.1
[0.2.0]: https://github.com/cashapp/turbine/releases/tag/0.2.0
[0.1.1]: https://github.com/cashapp/turbine/releases/tag/0.1.1
[0.1.0]: https://github.com/cashapp/turbine/releases/tag/0.1.0

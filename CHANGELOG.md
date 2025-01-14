## Unreleased

## v2.5.4 (2022-05-06)

### Refactor

- **telemetry**: instrument `process_resource` instead of `_process_resource`

## v2.5.3 (2022-05-05)

### Refactor

- rename `instrumentation` to `telemetry`

## v2.5.2 (2022-05-03)

### Fix

- remove telemetry require

## v2.5.1 (2022-05-03)

### Fix

- require instrumentation last

## v2.5.0 (2022-05-02)

### Feat

- **instrumentation**: trace `load_resources`

## v2.4.0 (2022-04-30)

### Feat

- **instrumentation**: add OpenTelemetry to `PlaceOS::Resource` ([#14](https://github.com/place-labs/resource/pull/14))

## v2.3.1 (2022-03-09)

## v2.3.0 (2022-01-19)

### Feat

- reconnect callback ([#12](https://github.com/place-labs/resource/pull/12))

## v2.2.0 (2021-10-15)

### Feat

- promise-3.0.0
- add `#startup_finished?`

### Fix

- retry if resource still open

## v2.0.5 (2021-07-30)

### Refactor

- lower log verbosity regarding event processing

## v2.0.4 (2021-07-15)

### Refactor

- less verbose message on `load_resource` finish

### Fix

- **rethinkdb-orm**: bump orm

## v2.0.3 (2021-07-08)

### Fix

- unwrap atomic

## v2.0.2 (2021-07-08)

### Fix

- serializable error

### Refactor

- use atomics
- use structs in favour of NamedTuples

## v1.2.1 (2021-04-13)

### Fix

- cause can be nillable

### Feat

- **error**: add `cause` to `ProcessingError`

### Perf

- allocate buffer the size of batches

## v1.0.6 (2021-02-23)

## v1.0.5 (2020-08-20)

## v1.0.4 (2020-08-20)

### Fix

- add Fiber.yield

## v1.0.3 (2020-08-18)

### Refactor

- ensure all event NamedTuples are identical

## v1.0.2 (2020-08-07)

### Fix

- retry changefeed

## v1.0.1 (2020-08-06)

## v1.0.0 (2020-07-17)

### Feat

- v1.0.0

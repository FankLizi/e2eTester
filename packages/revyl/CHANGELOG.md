# @e2e-dev/revyl

## 0.0.1

### Patch Changes

- [`0d92d6b`](https://github.com/e2e-inc/e2e/commit/0d92d6bff1564e566f4030506fc2680a9a8dce9b) - Add `@e2e-dev/revyl`: `revyl({ app, device, osVersion })` runs mobile targets on Revyl's hosted iOS simulators and Android emulators, one device per worker slot, through agent-device's `@agent-device/revyl` plugin. Set `REVYL_API_KEY` in the run environment; Revyl installs the build from the `https` `app` URL. Needs `@e2e-dev/mobile` 0.12.8 or later.

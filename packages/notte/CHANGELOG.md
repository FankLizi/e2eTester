# @e2e-dev/notte

## 0.0.1

### Patch Changes

- [`0d92d6b`](https://github.com/e2e-inc/e2e/commit/0d92d6bff1564e566f4030506fc2680a9a8dce9b) - New package: `notte()`, a browser provider that runs each test attempt in its own [Notte](https://notte.cc) cloud browser session, stops it when the attempt ends, reads `browser.waitForDownload` files back from the session's storage, and stops the sessions of workers that died when the run ends. [Notte browsers](https://e2e.com/docs/integrations/notte)

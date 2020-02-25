---
nav_order: 8
---

# Projects

## Gbkel

[Gbkel](https://coggle.it/diagram/XbwqkZL8UureOwi3/t/gbkel-api/a35fd20399966c595f461a1e09a78174650dac196df0e2c92b403681b5f90858) is a mix of personal services that communicate with each other in order to provide some solutions for myself.

It revolves around the following apps: **[portfolio](https://github.com/guilhermebkel/gbkel-portfolio), [thumb](https://github.com/guilhermebkel/gbkel-thumb), [admin](https://github.com/guilhermebkel/gbkel-admin), [api](https://github.com/guilhermebkel/gbkel-api), [worker](https://github.com/guilhermebkel/gbkel-worker)**.

The `portfolio` is managed by the `admin` app and each one consumes from the `api`.

The `api` has all the domain logic. Besides, everything such as report, upload, automation are processed in background by the `worker`.

The `thumb` provides thumbnails on demand for the `portfolio` with cdn support.

# daml-htlc

    Copyright (c) 2023, ASX Operations Pty Ltd. All rights reserved.
    SPDX-License-Identifier: Apache-2.0

Hashed timelock contract written in Daml.

# Building and testing
First, the dependencies must be downloaded by running:

```bash
./get-dependencies.sh
```

The daml package can then be built using:

```bash
daml build --project-root model/main
```

And the tests can be run using:

```bash
daml test --project-root model/main
```

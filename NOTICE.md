# Third-Party Dependencies and Licenses

This document provides attribution for third-party dependencies used in the Nuclear Fire Hose project. The core Trinity Architecture and novel orchestration logic remain the proprietary intellectual property of Quantum Encoding Ltd.

---

## Go Module Dependencies

### Direct Dependencies

#### github.com/nats-io/nats.go
- **License:** Apache License 2.0
- **Copyright:** Copyright 2012-2023 The NATS Authors
- **Repository:** https://github.com/nats-io/nats.go

#### github.com/prometheus/client_golang
- **License:** Apache License 2.0
- **Copyright:** Copyright 2015 The Prometheus Authors
- **Repository:** https://github.com/prometheus/client_golang

#### github.com/valyala/fasthttp
- **License:** MIT License
- **Copyright:** Copyright (c) 2015-present Aliaksandr Valialkin, VertaMedia, Kirill Danshin, Erik Dubbelboer, FastHTTP Authors
- **Repository:** https://github.com/valyala/fasthttp

#### github.com/iceber/iouring-go
- **License:** MIT License
- **Copyright:** Copyright (c) 2020 Iceber Gu
- **Repository:** https://github.com/iceber/iouring-go

#### golang.org/x/crypto
- **License:** BSD 3-Clause License
- **Copyright:** Copyright (c) 2009 The Go Authors. All rights reserved.
- **Repository:** https://golang.org/x/crypto

### Transitive Dependencies

#### github.com/klauspost/compress
- **License:** BSD 3-Clause License (Go) / MIT (Snappy)
- **Copyright:** Copyright (c) 2012 The Go Authors. All rights reserved. / Copyright (c) 2019 Klaus Post
- **Repository:** https://github.com/klauspost/compress

#### github.com/nats-io/nkeys
- **License:** Apache License 2.0
- **Copyright:** Copyright 2018-2023 The NATS Authors
- **Repository:** https://github.com/nats-io/nkeys

#### github.com/nats-io/nuid
- **License:** Apache License 2.0
- **Copyright:** Copyright 2016-2023 The NATS Authors
- **Repository:** https://github.com/nats-io/nuid

#### github.com/prometheus/client_model
- **License:** Apache License 2.0
- **Copyright:** Copyright 2012-2015 The Prometheus Authors
- **Repository:** https://github.com/prometheus/client_model

#### github.com/prometheus/common
- **License:** Apache License 2.0
- **Copyright:** Copyright 2015 The Prometheus Authors
- **Repository:** https://github.com/prometheus/common

#### github.com/prometheus/procfs
- **License:** Apache License 2.0
- **Copyright:** Copyright 2014 The Prometheus Authors
- **Repository:** https://github.com/prometheus/procfs

#### github.com/beorn7/perks
- **License:** MIT License
- **Copyright:** Copyright (C) 2013 Blake Mizerany
- **Repository:** https://github.com/beorn7/perks

#### github.com/cespare/xxhash/v2
- **License:** MIT License
- **Copyright:** Copyright (c) 2016 Caleb Spare
- **Repository:** https://github.com/cespare/xxhash

#### github.com/matttproud/golang_protobuf_extensions
- **License:** Apache License 2.0
- **Copyright:** Copyright 2012 Matt T. Proud
- **Repository:** https://github.com/matttproud/golang_protobuf_extensions

#### google.golang.org/protobuf
- **License:** BSD 3-Clause License
- **Copyright:** Copyright (c) 2018 The Go Authors. All rights reserved.
- **Repository:** https://google.golang.org/protobuf

#### golang.org/x/sys
- **License:** BSD 3-Clause License
- **Copyright:** Copyright (c) 2009 The Go Authors. All rights reserved.
- **Repository:** https://golang.org/x/sys

#### github.com/valyala/bytebufferpool
- **License:** MIT License
- **Copyright:** Copyright (c) 2016 Aliaksandr Valialkin
- **Repository:** https://github.com/valyala/bytebufferpool

#### github.com/andybalholm/brotli
- **License:** MIT License
- **Copyright:** Copyright (c) 2009, 2010, 2013-2016 by the Brotli Authors
- **Repository:** https://github.com/andybalholm/brotli

---

## Core Go Runtime

The Go programming language runtime and standard library are distributed under a BSD-style license:

**Copyright (c) 2009 The Go Authors. All rights reserved.**

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
* Neither the name of Google Inc. nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

---

## DPDK (Data Plane Development Kit)

If the compiled binary includes DPDK components:

- **License:** BSD 3-Clause License
- **Copyright:** Copyright(c) 2010-2023 Intel Corporation and contributors
- **Repository:** https://github.com/DPDK/dpdk

---

## Compliance Statement

All third-party dependencies listed above are used in compliance with their respective licenses. The permissive nature of these licenses (MIT, Apache 2.0, BSD) allows for their use in proprietary software provided proper attribution is given.

The core Trinity Architecture, custom DPDK adapter implementation, and the Nuclear Fire Hose orchestration logic remain the exclusive intellectual property of Quantum Encoding Ltd. and are protected under the terms specified in the LICENSE file.

---

*This NOTICE file was generated to ensure full legal compliance with open-source licensing requirements.*

© 2025 Quantum Encoding Ltd. All Rights Reserved.
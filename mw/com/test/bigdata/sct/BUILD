# *******************************************************************************
# Copyright (c) 2025 Contributors to the Eclipse Foundation
#
# See the NOTICE file(s) distributed with this work for additional
# information regarding copyright ownership.
#
# This program and the accompanying materials are made available under the
# terms of the Apache License Version 2.0 which is available at
# https://www.apache.org/licenses/LICENSE-2.0
#
# SPDX-License-Identifier: Apache-2.0
# *******************************************************************************

load("//platform/aas/tools/sctf/bazel_gen:sctf_gen.bzl", "py_sctf_test")

py_sctf_test(
    name = "mw_bigdata_test",
    srcs = [
        "__init__.py",
        "mw_bigdata_test.py",
    ],
    data = ["//platform/aas/mw/com/test/bigdata:bigdata-pkg.tar"],
    main = "mw_bigdata_test.py",
    module_root = "platform/aas/mw/com/test/bigdata/sct",
)

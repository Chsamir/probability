# Copyright 2020 The TensorFlow Probability Authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
# ============================================================================
# [internal] load pytype.bzl (pytype_strict_library)
# [internal] load dummy dependency

licenses(["notice"])

package(default_visibility = ["//visibility:public"])

# pytype_strict
py_library(
    name = "oryx",
    srcs = ["__init__.py"],
    srcs_version = "PY3",
    deps = [
        ":version",
        # jax dep,
        "//oryx/bijectors",
        "//oryx/core",
        "//oryx/distributions",
        "//oryx/experimental",
        "//oryx/internal",
        "//oryx/util",
    ],
)

# pytype_strict
py_library(
    name = "version",
    srcs = ["version.py"],
    srcs_version = "PY3",
)

# third_party_dependency(package = "py/oryx")  # DisableOnExport

# Copyright 2017 The TensorFlow Lattice Authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
# ==============================================================================
licenses(["notice"])  # Apache 2.0

package(
    default_visibility = [
        "//tensorflow_lattice:__subpackages__",
    ],
)

py_test(
    name = "pwl_calibration_test",
    size = "medium",
    srcs = ["pwl_calibration_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "@org_tensorflow//tensorflow:tensorflow_py",
        "//tensorflow_lattice/python:pwl_calibration_ops_py",
    ],
)

py_test(
    name = "lattice_gradient_test",
    size = "medium",
    srcs = ["lattice_gradient_test.py"],
    srcs_version = "PY2AND3",
    deps = [
        "@org_tensorflow//third_party/py/numpy",
        "@org_tensorflow//tensorflow:tensorflow_py",
        "//tensorflow_lattice/python:lattice_ops_py",
    ],
)

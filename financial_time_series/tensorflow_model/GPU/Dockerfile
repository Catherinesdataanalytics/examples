# Copyright 2018 The Kubeflow Authors All rights reserved.
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

FROM tensorflow/tensorflow:1.8.0-devel-gpu-py3

RUN pip3 install google-cloud-storage==1.10.0 \
                 google-cloud-bigquery==1.6.0 \
                 pandas==0.23.4 \
                 numpy==1.15.2

COPY . /opt/workdir
WORKDIR /opt/workdir

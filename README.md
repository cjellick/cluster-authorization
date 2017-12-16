cluster-authorization
========

Rancher Kubernetes controller that watches Rancher ClusterRoleTemplateBindings and ProjectRoleTemplateBindings and creates ClusterRoleBindings to the corresponding custom resources in the rancher management plane.

## Building

`make`


## Running

`./bin/cluster-authorization`

## License
Copyright (c) 2014-2017 [Rancher Labs, Inc.](http://rancher.com)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

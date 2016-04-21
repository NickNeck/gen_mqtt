# GenMQTT

An Elixir behaviour that makes it possible to communicate with a MQTT broker.


## Installation

This project is not available on hex as of yet. It can be installed by adding the following to the project mix-file:

``` elixir
  defp deps do
    [{:gen_mqtt, github: "gausby/gen_mqtt"}]
  end
```


## Legal stuff

This project rely on work done by [Erlio GmbH Basel Switzerland](http://erl.io), in specific the dependency [vmq_commons](https://github.com/erlio/vmq_commons/) which is released under an [Apache 2.0](https://github.com/erlio/vmq_commons/blob/master/LICENSE.txt)-license. This project, GenMQTT, is simply a wrapper on top of this work, and thus claim no copyright or ownership to any properties that belong to Erlio.

**Please notice**: Being a third party module all bug reports found in it should be raised directly in the [issues on this projects GitHub page](https://github.com/gausby/mqtt_tools/issues), unless it is a issue found in vmq_commons.


### License

Copyright 2016 Martin Gausby

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

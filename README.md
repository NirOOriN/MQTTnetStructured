
# MQTTnetStructured

Tis project is based on MQTTnet, see: https://github.com/dotnet/MQTTnet.

The main goal of this project is to abstract and strucutre it for a better usabillity, when using as a dependency.
Currently these are the main goals:

- Abstract/Interface implementations as far as possible/reasonable, e.g. MqttClientOptions, MqttTlsOptions and so on.
- Move abstractions into standalone projects/packages, allowing consumers to choose the correct packages when implementing.
- Move implmentations into seperate project/packages, allwoing consumers to choose the specific/wanted implementation, eg. Server, Client, ManagedClient.


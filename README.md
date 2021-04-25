Alibaba RSocket Broker Helm chart
=================================

Alibaba RSocket Broker is a communication system between broad range of applications using RSocket protocol.

# TL;DR;

```
helm repo add alibaba-rsocket-broker https://alibaba-rsocket-broker.github.io/helm/charts/
helm install rsocket-broker alibaba-rsocket-broker/alibaba-rsocket-broker
```

To test RSocket Broker services, please try

```
kubectl run -i --rm --tty rsocket-box --image=linuxchina/rsocket-box --restart=Never --image-pull-policy=Always
```

# References

* Alibaba RSocket Broker: https://github.com/alibaba/alibaba-rsocket-broker
* Alibaba RSocket Broker Wiki: https://github.com/alibaba/alibaba-rsocket-broker/wiki
* RSocket Home: https://rsocket.io/

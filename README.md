# Gatekeeper policies
Gatekeeper enforces admission control on Kubernetes: https://github.com/open-policy-agent/gatekeeper.

Feel free to read about this with some more details on [Medium](https://medium.com/technology-at-rombit/admission-control-on-kubernetes-9a1667b7e322).

This repository defines several policies for Gatekeeper on Kubernetes:
* prohibit usage of namespace default (or not defining a namespace)
* enforce usage of resource requests and limits
* usage of certain labels

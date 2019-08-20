# Gatekeeper policies
Gatekeeper enforces admission control on Kubernetes: https://github.com/open-policy-agent/gatekeeper.

This repository defines several policies for Gatekeeper on Kubernetes:
* prohibit usage of namespace default (or not defining a namespace)
* enforce usage of resource requests and limits
* usage of certain labels

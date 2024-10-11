## ConfigMap

ConfigMaps allow us to decouple our configurations from our container images.

## Ingress

In most cloud-based Kubernetes environments, you'll actually use an Ingress object to expose your services. The ingress object not only exposes your service to the outside world, but also allows you to do things like:

* Host multiple services on the same IP address
* Host multiple services on the same port (path-based routing)
* Terminate SSL
* Integrate directly with external DNS and load balancers


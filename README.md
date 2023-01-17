# EKS as a Service

This Configuration bundles an Upbound Cloud extension and an API definition. The
APIs will allow control planes to provision fully configured Amazon Elastic
Kubernetes Service (EKS) clusters with secure networking, composed using cloud
service primitives from the [Upbound Official AWS
Provider](https://marketplace.upbound.io/providers/upbound/provider-aws). App
deployments can securely connect to the infrastructure they need using secrets
distributed directly to the app namespace. The extension enables a hosted portal
in Upbound Cloud for interacting with your control plane’s APIs.

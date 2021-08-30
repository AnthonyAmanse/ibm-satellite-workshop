# Introduction

Satellite configuration allows you to specify what Kubernetes resources you want to deploy to a group of Red Hat OpenShift on IBM Cloud clusters that run in your Satellite location or in IBM Cloud.

![Example flow](.gitbook/assets/image%20%2826%29.png)

### Key Concepts

* Version
  * A version represents a Kubernetes/OpenShift resource like _Deployments, Services, ConfigMaps, etc._
* Subscription
  * A subscription is created in a Configuration that specifies which Version of the Kubernetes resource that you uploaded is deployed to one or more cluster groups.
* Cluster groups
  * A cluster group specifies a set of Red Hat OpenShift on IBM Cloud clusters that are registered with Satellite

### In this workshop...

You will learn:

* how the key concepts work
* how to create a Configuration and Version
* how to deploy the Version using Subscription
* how to use Subscription to roll deployments in cluster groups


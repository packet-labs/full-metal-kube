# Resource Me

Resource Me is the definitive index of bare metal Kubernetes 
resources on the Internet. It includes software, guides, use cases, 
blog posts, and lists of implementations to use on your 
bare metal Kubernetes. It will remain always up to date.

## Software

### MetalLB

MetalLB is a load-balancer implementation for bare metal Kubernetes 
clusters, using standard routing protocols. 

* https://metallb.universe.tf/

### Kubespray with Packet support

KubeSpray is a community project for deploying Kubernetes clusters on-premise 
or in the cloud. The project is based on Ansible playbooks and is covered by 
the Apache 2.0 license.

For general Kubespray information, please see:

* https://github.com/kubernetes-sigs/kubespray
* https://kubespray.io

Within the Kubespray project is support for bare metal Kubernetes through hosted on Packet.
This integration includes deployment of Packet bare metal infrastructure via Terraform,
the building of the inventory file used by the Ansible playbooks of Kubespray, and the 
setup of MetalLB for layer 3 load balancing via BGP.

For Packet on Kubespray information, please see:

https://github.com/kubernetes-sigs/kubespray/blob/master/contrib/terraform/packet/README.md


### Terraform Packet Provider

Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently.
The Packet Terraform provider is used to interact with the resources 
supported by Packet. 

https://www.terraform.io/docs/providers/packet/

### Terraform Packet BGP

`packet-bgp-terraform` is a Terraform template for setting up BGP on Packet.

* https://github.com/t0mk/packet-bgp-terraform/blob/master/main.tf

.. only:: not (epub or latex or html)

    WARNING! You are reading the "latest" Cilium documentation which is bleeding \
    edge and not meant for production use. Please read the stable versions from \
    http://docs.cilium.io

.. _kubernetes:

**********
Kubernetes
**********

Cilium provides seamless integration into Kubernetes. The following guidance may help you
to navigate this documentation section:

* If you are already a Kubernetes, Service and NetworkPolicy expert: `quickinstall`.
* If you are looking for a simple and safe playground to experiment with Cilium
  and Kubernetes `gs_minikube`.
* If you want to learn more about Cilium on Kubernetes first: `k8s_intro`.
* If you want to run Cilium on your kops cluster: `kops_guide`.

The following sections describe the Kubernetes integration in detail:

.. toctree::
   :maxdepth: 1
   :glob:

   quickinstall
   intro
   install
   policy
   ciliumendpoint
   troubleshooting

.. only:: not (epub or latex or html)

    WARNING! You are reading the "latest" Cilium documentation which is bleeding \
    edge and not meant for production use. Please read the stable versions from \
    http://docs.cilium.io

Step 1: Install Cilium
======================

The next step is to install Cilium into your Kubernetes cluster.
Cilium installation leverages the `Kubernetes Daemon Set
<https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/>`_
abstraction, which will deploy one Cilium pod per cluster node.  This
Cilium pod will run in the ``kube-system`` namespace along with all
other system relevant daemons and services.  The Cilium pod will run
both the Cilium agent and the Cilium CNI plugin.

Choose the installation instructions for the environment in which you are
deploying Cilium.

Docker Based
------------

`install_cilium_docker`

CRI-O Based
-----------

`install_cilium_crio`

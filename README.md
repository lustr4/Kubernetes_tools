# Kubernetes_tools
##  Ubuntu 22.04 Kubernetes v1.28 install instructions
Installation instructions for Kubernetes v1.28 on Ubuntu 22.04 with containerd as the container runtime and calico as the CNI plugin.
###  How to install control plane
Run script install_k8s_wcontrol_plane.sh

###  How to install worker node
Run script install_k8s_worker.sh
After the script run successfully the node can be joined after run the kubeadm join command that the master node outputs after kubeadm init.

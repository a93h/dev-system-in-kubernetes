# [README.md](./README.md) - updated: 8/11/2021
Steps:
 1. Install Vagrant (optional `vagrant plugin install vagrant-disksize`)
 2. Configure Vagrant file to your needs and computer's available resources. (cpu, mem, virtualbox vs vmware_*) (Currently targets $60 General Purpose Droplets 8GB memory and 2 CPUs)
 3. Search "CHANGE!" inside Vagrantfile to find items you might want to change.
 4. If you're using VMWare install the VMWare Vagrant utility.

Notes: The latest version of Kubernetes is not being used due to the fact that Helm doesn't yet support it.
Version Notes:

 - Kubernetes - 1.21.3-00
 - Helm - 3.6.3
 - Flannel - ~v0.14.0 - downloaded (8-10-2021)
 - Metallb - Latest from Helm
 - cert-manager - v1.0.4
 - Rancher - Latest from Helm
 - Traefik - Latest repo from Helm

Sources:
 - [Helm Skew (Version Support)](https://helm.sh/docs/topics/version_skew/)
 - [Jonas Werner Original Project](https://jonamiki.com/2019/11/09/kubernetes-home-lab-upgraded-edition-with-functional-loadbalancer-and-external-access-to-pods/)
 - [Vagrant](https://www.vagrantup.com/downloads)
 - [VMWare Vagrant](https://www.vagrantup.com/docs/providers/vmware/vagrant-vmware-utility)
 - [GitHub](https://github.com/jonas-werner/k8s-home-lab-with-vagrant)
 - [Flannel Use IP Address/NIC in Vagrant File](https://stackoverflow.com/questions/47845739/configuring-flannel-to-use-a-non-default-interface-in-kubernetes)
 - [Original Flannel Document](https://raw.githubusercontent.com/coreos/flannel/master/Documentation/kube-flannel.yml)
 - [Vagrant Disk Size](https://stackoverflow.com/questions/49822594/vagrant-how-to-specify-the-disk-size)
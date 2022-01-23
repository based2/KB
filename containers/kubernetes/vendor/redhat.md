https://www.openshift.com https://fabric8.io/

https://www.okd.io/
https://github.com/openshift/okd/
https://github.com/openshift/okd/releases
 3 cluster - 4 vCPU - 8 GB - 60GB SSD
oc adm release extract --tools quay.io/openshift/okd:4.5.0-0.okd-2020-07-14-153706-ga
openshift-install create cluster
openshift-install destroy cluster

https://formulae.brew.sh/formula/openshift-cli
https://rubix.nl/how-install-and-run-openshift-origin-your-mac-os-x/
  brew install openshift-cli
We have to add the registry 172.30.0.0/16 to our Docker Daemon through preferences -> Daemon and select Apply & Restart.
oc cluster up --docker-machine=openshift
oc cluster down --docker-machine=openshift

https://docs.okd.io/latest/welcome/
https://github.com/code-ready/crc


 https://github.com/openshift-cs/okd.io/blob/master/source/blog/slides/OKD-Workshop.pdf

https://commons.openshift.org/

# OpenShift on osx x86_64b amd64 - Experiment
https://luis-javier-arizmendi-alonso.medium.com/deploying-an-openshift-4-lab-in-a-kvm-node-using-libvirt-ipi-652f0476e8a5
https://ichi.pro/fr/deploiement-d-un-openshift-4-lab-dans-un-noeud-kvm-a-l-aide-de-libvirt-ipi-111252612769957

https://www.naut.ca/blog/2020/08/26/ubuntu-vm-on-macos-with-libvirt-qemu/
> https://news.ycombinator.com/item?id=24289769
  > https://multipass.run

# Canonical Multipass - Lightweight VM manager for Linux, Windows and MacOS (C++, GPL)
> https://multipass.run
  
> https://github.com/canonical/multipass

## Doc exploration
> multipass #250 -> #249 Inject custom image: #24
 > https://cloud-images.ubuntu.com (default)
 > https://uk.images.linuxcontainers.org LXC & LXD - Debian / Alpine / Devuan / Fedora
 > https://alt.fedoraproject.org/cloud
    
https://github.com/canonical/multipass/issues/1029 Unable to Launch an image using file:// and https:// option outside of Linux
    
note: https://pagure.io/cloud-sig/322 Open
https://ostechnix.com/how-to-create-and-launch-ubuntu-vms-with-multipass-on-linux/
https://www.ivankrizsan.se/2021/05/16/ansible-and-multipass-virtual-machines/
https://blog.ruanbekker.com/blog/2020/11/11/deploy-loki-on-multipass/

### Cloud-init
https://cloud-init.io

> https://cloudinit.readthedocs.io/en/latest

https://ubuntu.com/blog/using-cloud-init-with-multipass
  
https://fedoramagazine.org/setting-up-a-vm-on-fedora-server-using-cloud-images-and-virt-install-version-3/

### Image config
> #307

https://www.grottedubarbu.fr/introduction-cloud-init

multipass launch -n my_name -d 4G -m 1G bionic
-c CPU
-d disk
-m memory
multipass launch -n my_name -d 4G -m 1G https://alt.fedoraproject.org/cloud
multipass config
## Process
brew install --cask multipass
multipass version
multipass set client.primary-name=chaplin
multipass help launch
multipass launch -n charlot -d 64G -m 8G https://download.fedoraproject.org/pub/fedora/linux/releases/34/Cloud/x86_64/images/Fedora-Cloud-Base-34-1.2.x86_64.raw.xz
-> fails 

# Apple 'Big Sur' VZVirtualMachine
https://developer.apple.com/documentation/virtualization
> https://news.ycombinator.com/item?id=23922846
https://blog.xpnsec.com/bring-your-own-vm-mac-edition/
> https://github.com/KhaosT/SimpleVM  

# xhyve - unfinished
https://github.com/machyve/xhyve


# libvirt

# News
https://next.redhat.com/2022/01/19/introducing-microshift/ application that users can optionally deploy onto their field-deployed devices running an edge-optimized OS like RHEL (using its edge extension such as  rpm-ostree based transactional updates and greenboot-based auto-rollbacks designed for field-deployment)
> https://news.ycombinator.com/item?id=30004311
https://www.openshift.com

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
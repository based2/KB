https://spiffe.io/docs/latest/spiffe-about/overview/

https://www.bleepingcomputer.com/news/security/microsoft-finds-raspberry-robin-worm-in-hundreds-of-windows-networks/

https://www.openpolicyagent.org/

https://github.com/kyverno/kyverno/ Policy engine 

https://tldrsec.com/guides/kubernetes/ Risk8s Business: Risk Analysis of Kubernetes Clusters
https://blog.alcide.io/ubernetes-threat-vectors-part-5-defense-evasion

https://github.com/accuknox/kubearmor

https://www.microsoft.com/security/blog/2020/04/02/attack-matrix-kubernetes/
> https://news.ycombinator.com/item?id=22826710

https://github.com/kubernetes/kubernetes/issues/101493

https://sysdig.com/blog/lateral-movement-cloud-containers/

https://www.cyberark.com/resources/threat-research-blog/attacking-kubernetes-clusters-through-your-network-plumbing-part-2

https://buoyant.io/mtls-guide/
> https://news.ycombinator.com/item?id=28329878

https://kubernetes.io/docs/tasks/administer-cluster/encrypt-data/

https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2716980/nsa-cisa-release-kubernetes-hardening-guidance/
> https://media.defense.gov/2021/Aug/03/2002820425/-1/-1/0/CTR_Kubernetes_Hardening_Guidance_1.1_20220315.PDF
> https://www.reddit.com/r/netsec/comments/teulap/nsa_cisa_release_updated_kubernetes_hardening/

# Scanner
https://github.com/quay/clair Red Hat

https://iximiuz.com/en/posts/thick-container-vulnerabilities/

https://blog.cloudsecque.com/how-to-improve-the-security-of-your-applications-with-kubernetes-security-scanners-cda97fd2f574

# Secrets
https://kubernetes.io/docs/concepts/configuration/secret/

https://www.cncf.io/blog/2021/04/22/revealing-the-secrets-of-kubernetes-secrets/

https://newrelic.com/blog/how-to-relic/how-to-use-kubernetes-secrets

https://learn.hashicorp.com/tutorials/vault/kubernetes-sidecar

https://learn.hashicorp.com/tutorials/vault/kubernetes-secret-store-driver

https://blog.aquasec.com/managing-kubernetes-secrets

https://docs.openshift.com/container-platform/4.10/nodes/pods/nodes-pods-secrets.html

https://docs.bridgecrew.io/docs/bc_k8s_33

https://www.spectrocloud.com/blog/how-to-keep-your-kubernetes-secrets-secret/
> https://github.com/bitnami-labs/sealed-secrets
> https://www.godaddy.com/engineering/2019/04/16/kubernetes-external-secrets/
> https://github.com/hashicorp/vault-k8s

https://aws.amazon.com/en/blogs/france/aws-secrets-controller-comment-integrer-aws-secrets-manager-avec-kubernetes/

https://stackoverflow.com/questions/57596808/how-are-kubernetes-secrets-mounted

https://tanzu.vmware.com/developer/guides/platform-security-secrets-sa-what-is/
> tmpfs
> https://github.com/kubernetes/kubernetes/issues/48912 emptyDir with medium: Memory mounts a tmpfs volume without nosuid,nodev,noexec
> https://devops.pingidentity.com/how-to/usingVault/#using-tmpfs-for-secrets

https://medium.com/avmconsulting-blog/secrets-management-in-kubernetes-378cbf8171d0

https://www.akeyless.io/blog/secrets-injection-with-native-kubernetes-service-accounts-using-akeyless-vault-platform/

https://www.reddit.com/r/kubernetes/comments/zcfj1p/kubesealconvert_the_missing_part_of_sealed_secrets/

https://blog.gitguardian.com/how-to-handle-secrets-in-kubernetes/

https://thenewstack.io/hashicorp-vault-operator-manages-kubernetes-secrets/
> https://github.com/hashicorp/vault-secrets-operator/

# Forensic
https://github.com/checkpoint-restore/criu checkpoint/restore for Linux

https://github.com/falcosecurity/falcosidekick

https://github.com/draios/sysdig-inspect

# News
https://blog.doyensec.com/2024/01/23/k8s-scheduling-secure-design.html

https://thenewstack.io/tetragon-1-0-promises-a-new-era-of-kubernetes-security-and-observability/

https://blog.brakmic.com/keycloak-with-postgresql-on-kubernetes/
> https://news.ycombinator.com/item?id=35515873

https://kubernetes.io/blog/2023/03/10/forensic-container-analysis/

https://thenewstack.io/developer-guardrails-with-custom-kubernetes-resource-validators/

https://sysdig.com/blog/top-owasp-kubernetes/

https://sysdig.com/blog/top-15-kubectl-plugins-for-security-engineers/
> https://news.ycombinator.com/item?id=34835460

https://github.com/tinyzimmer/vault-rbac-controller

https://www.sdxcentral.com/articles/interview/cncf-accepts-kubescape-as-inaugural-open-source-security-scanner/2023/01/
> https://news.ycombinator.com/item?id=34343127

https://edgebit.io/enclaver/docs/0.x/deploy-kubernetes/ AWS Nitro
> https://github.com/edgebitio/enclaver
> https://www.reddit.com/r/kubernetes/comments/zsnofg/my_company_open_sourced_our_tool_to_mix_pods_with/

https://www.armosec.io/blog/kubernetes-security-cspm-blind-spot/

https://github.com/jodevsa/wireguard-operator
> https://www.reddit.com/r/kubernetes/comments/ytevgz/wireguard_operator/

https://blog.rewanthtammana.com/kubernetes-crd-validation-with-cel-and-kubebuilder-marker-comments

https://sysdig.com/blog/how-to-honeypot-vcluster-falco/
> https://www.reddit.com/r/kubernetes/comments/xvhlog/building_kubernetes_honeypots_with_vcluster_and/

https://research.nccgroup.com/2022/09/22/tool-release-project-kubescout-adding-kubernetes-support-to-scout-suite/

https://nirmata.com/2022/08/25/protect-the-pipe-secure-ci-cd-pipelines-with-a-policy-based-approach-using-tekton-and-kyverno/

https://github.com/edgelesssys/constellation shields entire Kubernetes clusters from the (cloud) infrastructure using confidential computing. Fedora CoreOS

https://owasp.org/www-project-kubernetes-top-ten/

https://thenewstack.io/introducing-open-source-zero-trust-to-kubernetes/

https://github.com/madhuakula/kubernetes-goat

https://github.com/google/gke-policy-automation
> https://news.ycombinator.com/item?id=32223271

https://thenewstack.io/shift-left-testing-applied-to-kubernetes/

https://sectool.co/blog/ebpf-based-security

https://blog.cloudflare.com/kubectl-with-zero-trust/

https://medium.com/@hosein.yousefi/vault-cluster-with-auto-unseal-on-kubernetes-8e469f9cdcfd
> https://www.reddit.com/r/kubernetes/comments/vie7y0/vault_cluster_with_auto_unseal_on_kubernetes/

https://blog.sectool.co/ebpf-based-security

https://github.com/PaloAltoNetworks/prisma-cloud-policies/tree/master/policies

https://sysdig.com/blog/atomic-red-team-falco/

https://www.cisecurity.org/benchmark/kubernetes

https://www.armosec.io/blog/secure-kubernetes-deployment/

https://smart7.in/2022/03/30/Kubernetes-Cluster-Attack-Defense-Importance-of-Network-Policies.html

https://madhuakula.com/kubernetes-goat/
> https://www.reddit.com/r/netsec/comments/ue2q4d/kubernetes_goat_interactive_kubernetes_security/

https://sysdig.com/blog/guide-kubernetes-forensics-dfir/

https://www.zdnet.com/article/nsa-and-cisa-heres-how-to-improve-your-kubernetes-cluster-security/

https://thenewstack.io/edgeless-systems-brings-confidential-computing-to-kubernetes/
> https://www.intel.com/content/www/us/en/developer/articles/technical/intel-trust-domain-extensions.html

https://github.com/cyberark/kubesploit

https://security.googleblog.com/2021/12/exploring-container-security-storage.html

https://media.defense.gov/2021/Aug/03/2002820425/-1/-1/1/CTR_KUBERNETES%20HARDENING%20GUIDANCE.PDF
> https://news.ycombinator.com/item?id=28050750

https://www.bleepingcomputer.com/news/security/attackers-deploy-cryptominers-on-kubernetes-clusters-via-argo-workflows/

https://sysdig.com/blog/crypto-mining-kubeflow-tensorflow-falco/

https://sysdig.com/blog/cve-2021-25735-kubernetes-admission-bypass/



Proxy it with a local registry:

> https://www.redhat.com/en/technologies/cloud-computing/quay Try & Buy

  https://docs.okd.io/1.5/install_config/registry/extended_registry_configuration.html
  
  Red Hat Quay v3.4.0 security update
  
> https://docs.docker.com/registry

  https://www.docker.com/blog/donating-docker-distribution-to-the-cncf/
  
    https://github.com/distribution/distribution

> https://goharbor.io/ CNCF VMware OSS


> https://help.sonatype.com/repomanager3/formats/docker-registry Nexus OSS/PROD

  https://support.sonatype.com/hc/en-us/sections/203012668-Security-Advisories

  https://shiro.apache.org/security-reports.html

> https://www.jfrog.com/confluence/display/JFROG/Docker+Registry JFrog Artifactory.

> http://port.us.org/ SUSE

> https://docs.gitlab.com/ee/user/packages/container_registry/

        https://www.digitalocean.com/community/tutorials/how-to-set-up-a-private-docker-registry-on-top-of-digitalocean-spaces-and-use-it-with-digitalocean-kubernetes

> https://pulpproject.org/content-plugins/ container
  
    https://github.com/verdaccio/verdaccio


https://containers.gitbook.io/build-containers-the-hard-way/


https://packages.debian.org/fr/sid/docker-registry


https://www.docker.com/blog/docker-registry-api-standardized-oci/ 2018

https://github.com/SteveLasker/RegistryArtifactTypes


https://landscape.cncf.io/card-mode?category=application-definition-image-build&grouping=category

https://en.wikipedia.org/wiki/Open_Container_Initiative

https://www.aquasec.com/cloud-native-academy/docker-container/docker-registry/


https://github.com/google/go-containerregistry

https://github.com/deislabs/oras

https://github.com/theupdateframework/notary Publish and verify content

https://github.com/cnabio/cnab-spec/blob/cnab-security-1.0.0-ga/300-CNAB-security.md

https://github.com/google/crfs CRFS: Container Registry Filesystem

https://github.com/containerd/stargz-snapshotter`

https://pkg.go.dev/github.com/google/crfs/stargz

https://github.com/opencontainers/artifacts/blob/master/artifact-authors.md

https://github.com/opencontainers/umoci

https://github.com/opencontainers/runtime-spec/blob/master/runtime.md
status (string, REQUIRED) is the runtime state of the container. The value MAY be one of:

    creating: the container is being created (step 2 in the lifecycle)
    created: the runtime has finished the create operation (after step 2 in the lifecycle), and the container process has neither exited nor executed the user-specified program
    running: the container process has executed the user-specified program but has not exited (after step 5 in the lifecycle)
    stopped: the container process has exited (step 7 in the lifecycle)
    Additional values MAY be defined by the runtime, however, they MUST be used to represent new runtime states not defined above.

https://github.com/awslabs/tough
> tough is a Rust client library for The Update Framework (TUF) repositories.
> tuftool is a Rust command-line utility for generating and signing TUF repositories.

https://github.com/opencontainers/runtime-tools

https://www.projectatomic.io/blog/2016/08/ocitools-libgen/

https://github.com/enseadaio/enseada

https://github.com/ContainerSolutions/trow

https://archive.fosdem.org/2020/schedule/event/containers_lazy_image_distribution/attachments/slides/3759/export/events/attachments/containers_lazy_image_distribution/slides/3759/stargz_snapshotter.pdf

https://www.fasten-project.eu/#
> https://linuxfr.org/news/presentation-du-projet-fasten-et-de-son-atelier-le-8-avril-2021
> > https://github.com/tern-tools/tern

https://github.com/features/packages#pricing

https://github.blog/2021-06-21-github-packages-container-registry-generally-available/

https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry

https://blog.aawadia.dev/2022/11/02/docker-registry-ci/
> https://news.ycombinator.com/item?id=33500807
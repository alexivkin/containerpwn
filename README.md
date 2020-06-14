# A collection of resources about container security

Check out the folders here:

* [Publications](Publications/)
* [Talks](Talks/)

[My BSides Seattle 2019 Talk](Talks/CircleCityCon-2020-Practical-security-in-the-brave-new-Kubernetes-world.pdf)

For Kubernetes related resources check my [other repo](https://github.com/alexivkin/kubepwn)


## Guides, tutorials and trainings

* [OWASP 2019 Container security training](https://github.com/alexivkin/Container-Security-Training)
* [Adidas training](https://github.com/ContainerSolutions/adidas)
* [Docker hardening](https://www.secjuice.com/how-to-harden-docker-containers/)
* [Docker secure deployment guides](https://github.com/GDSSecurity/Docker-Secure-Deployment-Guidelines)
* [OWASP's docker security](https://github.com/OWASP/Docker-Security)
* [Building containers, best practices](http://docs.projectatomic.io/container-best-practices/)
* [Docker security workshop](https://github.com/wurstbrot/docker-security-workshop)
* [Another Docker security workshop](https://github.com/docker-training/security-workshop)

## Concepts

* [Containers withouth docker](https://raesene.github.io/blog/2018/08/05/Docker-Containers-Without-Docker/)
* [Capabilities](https://raesene.github.io/blog/2017/08/27/Linux-capabilities-and-when-to-drop-all/)
* [Contained.af](https://github.com/genuinetools/contained.af)
* Running docker daemon without giving it [root privileges](https://docs.docker.com/engine/security/rootless/)

## Live training and demos

* [Katacoda](https://www.katacoda.com/courses/docker-security/)
* [Docker labs](https://github.com/docker/labs)

## Container escapes

* [Understanding Docker container escapes](https://blog.trailofbits.com/2019/07/19/understanding-docker-container-escapes/)
* [A Compendium of Container Escapes](https://i.blackhat.com/USA-19/Thursday/us-19-Edwards-Compendium-Of-Container-Escapes.pdf)

## Tools

* [Checking contianment primitives](https://github.com/genuinetools/amicontained)
* [Clair, a SCA-type tmage scanner](https://github.com/coreos/clair)
* [Google's tool for analyzing and comparing container images](https://github.com/GoogleContainerTools/container-diff)
* [Docker registry CLI tool](https://github.com/genuinetools/reg)
* [Unpack a Docker image](https://github.com/larsks/undocker)

## Standards and recommendations

* [CIS Benchmark](https://www.cisecurity.org/benchmark/docker/)
* [Docker bench for security - CIS Benchmark checker](https://github.com/docker/docker-bench-security)

## Windows

* Good intro presentation to docker and docker on windows - <https://stefanscherer.github.io/windows-docker-workshop/#1> (includes some workarounds like mounting drive to help in real-path resolution for mapped volumes)
* Docker on windows - Microsoft docs - https://docs.microsoft.com/en-us/virtualization/windowscontainers/manage-docker/configure-docker-daemon
* MS Containers documentation <https://docs.microsoft.com/en-us/virtualization/windowscontainers/index>
* Windows docker tutorials - <https://github.com/docker/labs/tree/master/windows>
* Nano server - <https://docs.microsoft.com/en-us/windows-server/get-started/getting-started-with-nano-server>
* Docker compose on windows [https://github.com/docker/labs/blob/master/windows/windows-containers/MultiContainerApp.md](https://docs.microsoft.com/en-us/virtualization/windowscontainers/index)
* How docker for windows runs Linux containers - <https://docs.microsoft.com/en-us/virtualization/windowscontainers/deploy-containers/linux-containers>
* Hyper-V considerations -<https://blog.docker.com/2016/10/considerations-running-docker-windows-server-2016-hyper-v-vms/>
* Docker GUI - <http://wiki.ros.org/docker/Tutorials/GUI>
* Installing WSL and docker - https://raesene.github.io/blog/2018/03/29/WSL-And-Docker/

## Docker registry

* how docker registry authorization is done - https://medium.com/@maanadev/authorization-for-private-docker-registry-d1f6bf74552f

## Monitoring

* monitoring containers - https://katacoda.com/sysdig/scenarios/sysdig-container-visibility
* monitoring with sysdig - https://www.katacoda.com/courses/docker-security/sysdig-falco

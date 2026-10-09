# George Sopin

DevOps engineer with a development background. I set up delivery from commit to
cluster and run the cluster itself. Led a development team on a commercial
project, and still write the services that live in the infrastructure I build.

Software Engineering student at RTU MIREA, Moscow. Writing code since 2020.

---

### Infrastructure

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-326CE5?style=for-the-badge&logo=linux&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-326CE5?style=for-the-badge&logo=istio&logoColor=white)
![Calico](https://img.shields.io/badge/Calico-326CE5?style=for-the-badge)
![cert-manager](https://img.shields.io/badge/cert--manager-326CE5?style=for-the-badge&logo=letsencrypt&logoColor=white)
![containerd](https://img.shields.io/badge/containerd-326CE5?style=for-the-badge&logo=containerd&logoColor=white)
![cri-o](https://img.shields.io/badge/cri--o-326CE5?style=for-the-badge&logo=cri-o&logoColor=white)
![MetalLB](https://img.shields.io/badge/MetalLB-326CE5?style=for-the-badge)
![Flannel](https://img.shields.io/badge/Flannel-326CE5?style=for-the-badge)
![Nginx](https://img.shields.io/badge/Nginx-326CE5?style=for-the-badge&logo=nginx&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-326CE5?style=for-the-badge&logo=proxmox&logoColor=white)
![Packer](https://img.shields.io/badge/Packer-326CE5?style=for-the-badge&logo=packer&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-326CE5?style=for-the-badge&logo=ansible&logoColor=white)
![Talos Linux](https://img.shields.io/badge/Talos%20Linux-326CE5?style=for-the-badge&logo=talos&logoColor=white)
![cloud-init](https://img.shields.io/badge/cloud--init-326CE5?style=for-the-badge&logo=ubuntu&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-326CE5?style=for-the-badge&logo=wireguard&logoColor=white)
![Hyper-V](https://img.shields.io/badge/Hyper--V-326CE5?style=for-the-badge)

Hand-provisioned with kubeadm: a 5-node cluster with a 3-master HA control plane.
Golden VM images for Proxmox built with Packer: Ubuntu autoinstall, Kubernetes
node images, Talos Image Factory schematics. Every template is tested by booting a clone.

### Delivery

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-B45309?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-B45309?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-B45309?style=for-the-badge&logo=git&logoColor=white)
![Nexus](https://img.shields.io/badge/Nexus-B45309?style=for-the-badge&logo=sonatype&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-B45309?style=for-the-badge&logo=gnubash&logoColor=white)
![Renovate](https://img.shields.io/badge/Renovate-B45309?style=for-the-badge&logo=renovate&logoColor=white)
![pre-commit](https://img.shields.io/badge/pre--commit-B45309?style=for-the-badge&logo=precommit&logoColor=white)

From commit to cluster in one pipeline: tests, image builds with Docker Buildx,
publishing to a self-hosted registry, rollout to Kubernetes.

### Security & supply chain

![OpenSCAP](https://img.shields.io/badge/OpenSCAP-9F1239?style=for-the-badge)
![Trivy](https://img.shields.io/badge/Trivy-9F1239?style=for-the-badge&logo=trivy&logoColor=white)
![goss](https://img.shields.io/badge/goss-9F1239?style=for-the-badge)
![gitleaks](https://img.shields.io/badge/gitleaks-9F1239?style=for-the-badge)
![ShellCheck](https://img.shields.io/badge/ShellCheck-9F1239?style=for-the-badge)
![zizmor](https://img.shields.io/badge/zizmor-9F1239?style=for-the-badge)
![OpenSSF Scorecard](https://img.shields.io/badge/OpenSSF%20Scorecard-9F1239?style=for-the-badge&logo=openssf&logoColor=white)

Images scanned against the CIS Level 1 benchmark with OpenSCAP and for CVEs with Trivy,
verified with goss. Hardened CI: actions pinned by SHA, minimal permissions, secrets
scoped to protected environments; the cloud runner reaches the lab only through
a per-job WireGuard peer, nothing is exposed to the internet. OpenSSF Best Practices
passing badge and Scorecard.

### Data & observability

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-2F6F4E?style=for-the-badge&logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-2F6F4E?style=for-the-badge&logo=apachekafka&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-2F6F4E?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-2F6F4E?style=for-the-badge&logo=grafana&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-2F6F4E?style=for-the-badge&logo=keycloak&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-2F6F4E?style=for-the-badge&logo=mongodb&logoColor=white)
![CloudNativePG](https://img.shields.io/badge/CloudNativePG-2F6F4E?style=for-the-badge&logo=postgresql&logoColor=white)
![Strimzi](https://img.shields.io/badge/Strimzi-2F6F4E?style=for-the-badge&logo=apachekafka&logoColor=white)
![Alertmanager](https://img.shields.io/badge/Alertmanager-2F6F4E?style=for-the-badge&logo=prometheus&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-2F6F4E?style=for-the-badge&logo=mysql&logoColor=white)

Stateful workloads through operators, not hand-written manifests.
SSO on Keycloak, internal dashboards behind OAuth2 Proxy.

### Development

![Java](https://img.shields.io/badge/Java-6E5494?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6E5494?style=for-the-badge&logo=spring&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-6E5494?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-6E5494?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-6E5494?style=for-the-badge&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-6E5494?style=for-the-badge&logo=rust&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-6E5494?style=for-the-badge&logo=junit5&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI-6E5494?style=for-the-badge&logo=openapiinitiative&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-6E5494?style=for-the-badge&logo=gradle&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-6E5494?style=for-the-badge&logo=apachemaven&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-6E5494?style=for-the-badge&logo=cmake&logoColor=white)
![NASM](https://img.shields.io/badge/NASM-6E5494?style=for-the-badge)
![GAS](https://img.shields.io/badge/GAS-6E5494?style=for-the-badge)
![FASM](https://img.shields.io/badge/FASM-6E5494?style=for-the-badge)

Microservices in Java with Spring Boot. Systems code in C and C++: freestanding
environments without libc, manual memory management, ELF and the linker.
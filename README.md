# Awesome Home Kubernetes

A curation of projects and resources involving running Kubernetes at home. ⛵

- [Awesome Home Kubernetes](#awesome-home-kubernetes)
  - [Home GitOps Kubernetes Clusters](#home-gitops-kubernetes-clusters)
  - [Helm Chart Repositories](#helm-chart-repositories)

## Home GitOps Kubernetes Clusters

[![search-users](https://img.shields.io/badge/search-repos-orange?style=for-the-badge)](https://sourcegraph.com/search?q=%28repo%3A%5Egithub%5C.com%2Fams0%2Francher-home%24+or+repo%3A%5Egithub%5C.com%2Fangelnu%2Fk8s-gitops%24+or+repo%3A%5Egithub%5C.com%2Fanthr76%2Finfra%24+or+repo%3A%5Egithub%5C.com%2Fauricom%2Fhome-cluster%24+or+repo%3A%5Egithub%5C.com%2Fbillimek%2Fk8s-gitops%24+or+repo%3A%5Egithub%5C.com%2Fbjw-s%2Fhome-ops%24+or+repo%3A%5Egithub%5C.com%2Fblackjid%2Fk8s-gitops%24+or+repo%3A%5Egithub%5C.com%2Fbudimanjojo%2Fhome-cluster%24+or+repo%3A%5Egithub%5C.com%2Fbuvis-net%2Fcluster%24+or+repo%3A%5Egithub%5C.com%2Fcarpenike%2Fk8s-gitops%24+or+repo%3A%5Egithub%5C.com%2Fcbirkenbeul%2Fk3s-gitops%24+or+repo%3A%5Egithub%5C.com%2Fcharlie-haley%2Fhome-cluster%24+or+repo%3A%5Egithub%5C.com%2FDiaoul%2Fhome-ops%24+or+repo%3A%5Egithub%5C.com%2Fdirtycajunrice%2Fgitops%24+or+repo%3A%5Egithub%5C.com%2Ffobiat%2Fk8s-gitops%24+or+repo%3A%5Egithub%5C.com%2Fjr0dd%2Fhome-ops%24+or+repo%3A%5Egithub%5C.com%2Fkhuedoan%2Fhomelab%24+or+repo%3A%5Egithub%5C.com%2Fkitos9112%2Fk8s-home%24+or+repo%3A%5Egithub%5C.com%2Flanquarden%2Froci-gitops%24+or+repo%3A%5Egithub%5C.com%2Flib42%2Fheqet%24+or+repo%3A%5Egithub%5C.com%2Fmcfio%2FGitOps%24+or+repo%3A%5Egithub%5C.com%2Fnicholaswilde%2Fhome-cluster%24+or+repo%3A%5Egithub%5C.com%2Fnpawelek%2Fk8s-gitops%24+or+repo%3A%5Egithub%5C.com%2Fonedr0p%2Fhome-cluster%24+or+repo%3A%5Egithub%5C.com%2Fp3lim%2Frudder%24+or+repo%3A%5Egithub%5C.com%2Fphybros%2Fk3s-cluster%24+or+repo%3A%5Egithub%5C.com%2Frust84%2Fk8s-gitops%24+or+repo%3A%5Egithub%5C.com%2Frwaltr%2Finfra%24+or+repo%3A%5Egithub%5C.com%2Ftimtorchen%2Fpi-cluster%24+or+repo%3A%5Egithub%5C.com%2Ftoboshii%2Fhome-cluster%24+or+repo%3A%5Egithub%5C.com%2Ftodaywasawesome%2Fatomic-cluster%24+or+repo%3A%5Egithub%5C.com%2Fvaskozl%2Fhome-infra%24+or+repo%3A%5Egithub%5C.com%2FWRMilling%2Fk3s-gitops%24+or+repo%3A%5Egithub%5C.com%2Fxunholy%2Fk8s-gitops%24+or+repo%3A%5Egithub%5C.com%2Fzacheryph%2Fk8s-gitops%24+or+repo%3A%5Egithub%5C.com%2Fzbigniewzolnierowicz%2Fk8s-home%24+or+repo%3A%5Egithub%5C.com%2Fzenxedo%2Fk3s-gitops%24%29+count%3A2000&patternType=literal)
[![search-users](https://img.shields.io/badge/search-users-orange?style=for-the-badge)](https://sourcegraph.com/search?q=%28repo%3A%5Egithub%5C.com%2Fams0%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fangelnu%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fanthr76%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fauricom%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fbillimek%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fbjw-s%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fblackjid%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fbudimanjojo%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fbuvis-net%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fcarpenike%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fcbirkenbeul%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fcharlie-haley%2F.%2A+or+repo%3A%5Egithub%5C.com%2FDiaoul%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fdirtycajunrice%2F.%2A+or+repo%3A%5Egithub%5C.com%2Ffobiat%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fjr0dd%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fkhuedoan%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fkitos9112%2F.%2A+or+repo%3A%5Egithub%5C.com%2Flanquarden%2F.%2A+or+repo%3A%5Egithub%5C.com%2Flib42%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fmcfio%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fnicholaswilde%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fnpawelek%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fonedr0p%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fp3lim%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fphybros%2F.%2A+or+repo%3A%5Egithub%5C.com%2Frust84%2F.%2A+or+repo%3A%5Egithub%5C.com%2Frwaltr%2F.%2A+or+repo%3A%5Egithub%5C.com%2Ftimtorchen%2F.%2A+or+repo%3A%5Egithub%5C.com%2Ftoboshii%2F.%2A+or+repo%3A%5Egithub%5C.com%2Ftodaywasawesome%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fvaskozl%2F.%2A+or+repo%3A%5Egithub%5C.com%2FWRMilling%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fxunholy%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fzacheryph%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fzbigniewzolnierowicz%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fzenxedo%2F.%2A%29+count%3A2000&patternType=literal)

| Repository                                                      | Description                            |
| --------------------------------------------------------------- | -------------------------------------- |
| [ams0/rancher-home](https://github.com/ams0/rancher-home)             | RKE+Terraform-deployed cluster, with Fluxv1 ([video](https://www.youtube.com/watch?v=JrBo3UCe6ds&t=1375s))        |
| [angelnu/k8s-gitops](https://github.com/angelnu/k8s-gitops)             | Flux/GitOps k3s HA clusters (staging/production) built with Ansible/Proxmox. Use Ceph, Zalando Postgres and SOPS for persistency.)        |
| [anthr76/infra](https://github.com/anthr76/infra)             | Flux/Gitops mixed architecture managed clusters for homelab cololocations built with Talos and Sidero for netboot to Kubernetes on arm64 + amd64        |
| [auricom/home-cluster](https://github.com/auricom/home-cluster)             | Flux2/Gitops managed cluster running on k3s        |
| [billimek/k8s-gitops](https://github.com/billimek/k8s-gitops)             | GitOps principles to define kubernetes k3s cluster state via code, running on mixed-architecture hardware with infra config in [billimek/homelab-infrastructure](https://github.com/billimek/homelab-infrastructure)        |
| [bjw-s/home-ops](https://github.com/bjw-s/home-ops)             | Flux/GitOps managed Talos        |
| [blackjid/k8s-gitops](https://github.com/blackjid/k8s-gitops)             | Flux/GitOps managed cluster built with Terraform and libvirt at [blackjid/homelab-infra](https://github.com/blackjid/homelab-infra)        |
| [budimanjojo/home-cluster](https://github.com/budimanjojo/home-cluster)             | Flux2/GitOps managed k3s cluster built without helm.        |
| [buvis-net/cluster](https://github.com/buvis-net/cluster)             | ARM64 based k3s cluster managed by Flux2        |
| [carpenike/k8s-gitops](https://github.com/carpenike/k8s-gitops)             | Flux/GitOps managed cluster built with kubeadm [carpenike/home-infra](https://github.com/carpenike/home-infra)        |
| [cbirkenbeul/k3s-gitops](https://github.com/cbirkenbeul/k3s-gitops)             | Flux2/GitOps managed k3s cluster running on mixed architecture.        |
| [charlie-haley/home-cluster](https://github.com/charlie-haley/home-cluster)             | Multi-architecture, Flux managed cluster - provisioned with Sidero.        |
| [Diaoul/home-ops](https://github.com/Diaoul/home-ops)             | Flux/GitOps managed k3s cluster with Ansible        |
| [dirtycajunrice/gitops](https://github.com/dirtycajunrice/gitops)             | Argo CD managed cluster        |
| [fobiat/k8s-gitops](https://github.com/fobiat/k8s-gitops)             | Flux2/GitOps managed cluster running on k8s        |
| [jr0dd/home-ops](https://github.com/jr0dd/home-ops)             | One repo to rule them all. This serves my home infrastructure and Kubernetes cluster        |
| [khuedoan/homelab](https://github.com/khuedoan/homelab)             | Fully automated Kubernetes cluster from empty hard drives to running services with a single command (using PXE boot, k3s and ArgoCD).        |
| [kitos9112/k8s-home](https://github.com/kitos9112/k8s-home)             | Flux/GitOps managed K3s home cluster running on ARM64 and AMD64 hardware        |
| [lanquarden/roci-gitops](https://github.com/lanquarden/roci-gitops)             | Flux/GitOps managed k3s HA cluster built with Ansible at [lanquarden/home-operations](https://github.com/lanquarden/home-operations)        |
| [lib42/heqet](https://github.com/lib42/heqet)             | Argo-CD Plugin & Helm-Chart using the App-of-Apps pattern & abstraction to make GitOps deployments simple & DRY. [[see docs](https://lib42.github.io/heqet) / [My Homelab](https://github.com/nold360/hive-apps)]        |
| [mcfio/GitOps](https://github.com/mcfio/GitOps)             | ARM64 based Kubernetes cluster managed by FluxV2, using Git as a 'single source of truth.'        |
| [nicholaswilde/home-cluster](https://github.com/nicholaswilde/home-cluster)             | Flux/GitOps managed k3s cluster running on an arm64 [Turing Pi 1](https://turingpi.com/)        |
| [npawelek/k8s-gitops](https://github.com/npawelek/k8s-gitops)             | Flux2/GitOps managed cluster built with Ansible and kubeadm        |
| [onedr0p/home-cluster](https://github.com/onedr0p/home-cluster)             | Running Flux and built with Ansible        |
| [p3lim/rudder](https://github.com/p3lim/rudder)             | Flux managed [Talos](https://talos.dev) cluster        |
| [phybros/k3s-cluster](https://github.com/phybros/k3s-cluster)             | Flux/GitOps managed k3s home cluster        |
| [rust84/k8s-gitops](https://github.com/rust84/k8s-gitops)             | Flux/GitOps managed k3s cluster running on mixed-architecture.        |
| [rwaltr/infra](https://github.com/rwaltr/infra)             | Argo/Terraform Managed Multi Cluster design.        |
| [timtorchen/pi-cluster](https://github.com/timtorchen/pi-cluster)             | Helmfile managed k3s cluster, with sops securing secrets        |
| [toboshii/home-cluster](https://github.com/toboshii/home-cluster)             | Flux2/GitOps managed k3s cluster deployed on Proxmox using Terraform and Ansible.        |
| [todaywasawesome/atomic-cluster](https://github.com/todaywasawesome/atomic-cluster)             | 5-node home lab x86/arm built on Atomic Pis for under $250.        |
| [vaskozl/home-infra](https://github.com/vaskozl/home-infra)             | Flux2 Raspberry Pi cluster running crème de la crème FOSS        |
| [WRMilling/k3s-gitops](https://github.com/WRMilling/k3s-gitops)             | Flux2/GitOps managed k3s cluster running on mixed-architecture hardware (AMD64 + ARM64) as defined in [WRMilling/homelab-infrastructure](https://github.com/WRMilling/homelab-infrastructure)        |
| [xunholy/k8s-gitops](https://github.com/xunholy/k8s-gitops)             | Home Kubernetes cluster managed by GitOps on Raspberry Pis with Ansible at [kubeflare/k8s-cluster-installation](https://github.com/raspbernetes/k8s-cluster-installation)        |
| [zacheryph/k8s-gitops](https://github.com/zacheryph/k8s-gitops)             | Flux/GitOps managed cluster, on k3os (cloud-init in `/k3os`)        |
| [zbigniewzolnierowicz/k8s-home](https://github.com/zbigniewzolnierowicz/k8s-home)             | Flux2/Gitops managed cluster running on k3s        |
| [zenxedo/k3s-gitops](https://github.com/zenxedo/k3s-gitops)             | Flux/GitOps managed k3s cluster        |

## Helm Chart Repositories

[![search-charts](https://img.shields.io/badge/search-repos-orange?style=for-the-badge)](https://sourcegraph.com/search?q=%28repo%3A%5Egithub%5C.com%2Fhalkeye%2Fhelm-charts%24+or+repo%3A%5Egithub%5C.com%2Fk8s-at-home%2Fcharts%24+or+repo%3A%5Egithub%5C.com%2Fnicholaswilde%2Fhelm-charts%24+or+repo%3A%5Egithub%5C.com%2Ftruecharts%2Fapps%24%29+count%3A2000&patternType=literal)
[![search-charts](https://img.shields.io/badge/search-users-orange?style=for-the-badge)](https://sourcegraph.com/search?q=%28repo%3A%5Egithub%5C.com%2Fhalkeye%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fk8s-at-home%2F.%2A+or+repo%3A%5Egithub%5C.com%2Fnicholaswilde%2F.%2A+or+repo%3A%5Egithub%5C.com%2Ftruecharts%2F.%2A%29+count%3A2000&patternType=literal)

| Repository                                                      | Description                            |
| --------------------------------------------------------------- | -------------------------------------- |
| [halkeye/helm-charts](https://halkeye.github.io/helm-charts)             | [@halkeye](https://github.com/halkeye)'s collection of Helm charts.        |
| [k8s-at-home/charts](https://github.com/k8s-at-home/charts)             | Helm charts for applications you run at home.        |
| [nicholaswilde/helm-charts](https://github.com/nicholaswilde/helm-charts)             | [@nicholaswilde](https://github.com/nicholaswilde)'s collection of Helm charts.        |
| [truecharts/apps](https://github.com/truecharts/apps)             | Charts that work with [TrueNAS SCALE](https://www.truenas.com/truenas-scale/).        |

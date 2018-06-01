# Information comes from [ramitsurana/awesome-kubernetes](https://github.com/ramitsurana/awesome-kubernetes)
Awesome-Kubernetes
=======================================================================

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://travis-ci.org/ramitsurana/awesome-kubernetes.svg?branch=master)](https://travis-ci.org/ramitsurana/awesome-kubernetes)
[![Build Status](https://semaphoreci.com/api/v1/ramitsurana/awesome-kubernetes/branches/master/badge.svg)](https://semaphoreci.com/ramitsurana/awesome-kubernetes)
[![License](https://img.shields.io/badge/License-CC%204.0-brightgreen.svg?style=flat-square)](http://creativecommons.org/licenses/by-nc/4.0/)
[![Docker Build Status](https://img.shields.io/docker/build/ramitsurana/awesome-kubernetes.svg?style=flat-square)](https://hub.docker.com/r/ramitsurana/awesome-kubernetes)
[![Slack Widget](https://camo.githubusercontent.com/984828c0b020357921853f59eaaa65aaee755542/68747470733a2f2f73332e65752d63656e7472616c2d312e616d617a6f6e6177732e636f6d2f6e6774756e612f6a6f696e2d75732d6f6e2d736c61636b2e706e67)](https://kubernetes.slack.com/messages/awesome-kubernetes)


A curated list for awesome kubernetes sources
Inspired by [@sindresorhus' awesome](https://github.com/sindresorhus/awesome)

![final-k8s](https://cloud.githubusercontent.com/assets/8342133/26794201/62c1a006-4a3e-11e7-8bf9-4449814648f2.png)

> "Talent wins games, but teamwork and intelligence wins championships."
>
> -- Michael Jordan

Without the help from these [amazing contributors](https://github.com/ramitsurana/awesome-kubernetes/graphs/contributors),
building this awesome-repo would never has been possible. Thank You very much guys !!

**Thanks to Gitbook.This awesome list can now be downloaded and read in the form of a book.Check it out -->  https://www.gitbook.com/book/ramitsurana/awesome-kubernetes/ .Keep Learning Keep Sharing !!**

**If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!**

## What is Kubernetes? :ship:

> Kubernetes is an open source orchestration system for Docker containers. It handles scheduling onto nodes in a compute cluster and actively manages workloads to ensure that their state matches the users declared intentions. Using the concepts of "labels" and "pods", it groups the containers which make up an application into logical units for easy management and discovery.

_Source:_ [What is Kubernetes](http://kubernetes.io/)


## History:

**Kubernetes is known to be a descendant of Google's system BORG**

> The first unified container-management system developed at Google was the system we internally call Borg.
It was built to manage both long-running services and batch jobs, which had previously been handled by two separate
systems: Babysitter and the Global Work Queue. The latter’s architecture strongly influenced Borg, but was focused on
batch jobs; both predated Linux control groups.

_Source:_ [Kubernetes Past](http://research.google.com/pubs/archive/44843.pdf)

## Date of Birth:

Kubernetes celebrates its birthday every year on 21st July. Kubernetes 1.0 was released on July 21 2015, after being first announced to the public at [Dockercon in June 2014](https://www.youtube.com/watch?v=YrxnVKZeqK8).

## Roadmap

The awesome-kubernetes will now soon be available in the form of different releases and package bundles, It means that you can
download the awesome kubernetes release up to a certain period of time, The release for awesome kubernetes 2015 bundle is released.Checkout the releases column for more info.Stay tuned for more updates.

-----------------------------------------------------------------------


Menu
=======================================================================

* [Starting Point](#starting-point)
* [Installers](#installers)
* [Main Resources](#main-resources)
* [Release Notes](#release-notes)
* [Useful Articles](#useful-articles)
* [Managed Kubernetes](#managed-kubernetes)
  * [Developer Platform](#developer-platform)
  * [Enterprise Kubernetes Products](#enterprise-kubernetes-products)
  * [Public/Private Cloud](#publicprivate-cloud)
  * [Paas](#paas)
* [Interactive Learning Environments](#interactive-learning-environments)
* [MOOC Courses / Tutorials](#courses-or-tutorials)
* [Case Studies](#case-studies)
* [Persistent Volume Providers](#persistent-volume-providers)
* [Useful Libraries/Scripts](#developer-libraries-scripts)
  * [Python](#python)
  * [Jenkins](#jenkins)
* [Projects](#projects)
  * [Related Software](#related-software)
* [Monitoring Services](#monitoring-services)
* [Testing](#testing)
* [Continuous Delivery](#continuous-delivery)
* [Serverless Implementations](#serverless-implementations)
* [Operators](#operators)
* [Custom Schedulers](#custom-schedulers)
* [Container Support](#container-support)
* [Database/NoSQL](#database)
* [Networking](#networking)
* [Service mesh](#service-mesh)
* [RPC](#rpc)
* [Secret generation and management](#secret-generation-and-management)
* [Web applications](#web-applications)
* [Desktop applications](#desktop-applications)
* [Mobile applications](#mobile-applications)
* [API/CLI adaptors](#apicli-adaptors)
* [Application deployment orchestration](#application-deployment-orchestration)
* [Configuration](#configuration)
* [Security](#security)
* [Load balancing](#load-balancing)
* [Developer platform](#developer-platform)
* [Big Data](#big-data)
* [Machine Learning](#machine-learning)
* [Service Discovery](#service-discovery)
* [Operating System](#operating-system)
* [YAML/JSON Config](#yamljson-config)
* [Tuning](#tuning)
* [Backup and Disaster Recovery](#backup-and-disaster-recovery)
* [Raspberry Pi](#raspberry-pi)
* [Books](#books) :books:
* [Slide Presentations](#slide-presentations)
* [Videos](#videos) :tv:
  * [Main Account](#main-account)
  * [Other Useful videos](#other-useful-videos)
* [Interesting Twitter Accounts](#interesting-twitter-accounts)
* [Amazing People](#amazing-people)
* [Meetup Groups](#meetup-groups)
* [Connecting with Kubernetes](#connecting-with-kubernetes)
* [Conferences](#conferences)
* [Contributing](#contributing)
* [License](#license)


-----------------------------------------------------------------------


Starting Point
=======================================================================

*A place that marks the beginning of a journey*

* [Kubernetes Community Overview and Contributions Guide](https://docs.google.com/presentation/d/1JqcALpsg07eH665ZXQrIvOcin6SzzsIUjMRRVivrZMg/edit?usp=sharing) by [Ihor Dvoretskyi](https://twitter.com/idvoretskyi/)
* [Are you Ready to Manage your Infrastructure like Google?](http://blog.jetstack.io/blog/k8s-getting-started-part1/)
* [Google is years ahead when it comes to the cloud, but it's happy the world is catching up](http://www.businessinsider.in/Google-is-years-ahead-when-it-comes-to-the-cloud-but-its-happy-the-world-is-catching-up/articleshow/47793327.cms)
* [An Intro to Google’s Kubernetes and How to Use It](http://www.ctl.io/developers/blog/post/what-is-kubernetes-and-how-to-use-it/) by [Laura Frank](https://twitter.com/rhein_wein)
* [Getting Started on Kubernetes](http://containertutorials.com/get_started_kubernetes/index.html) by [Rajdeep Dua](https://twitter.com/rajdeepdua)
* [Kubernetes: The Future of Cloud Hosting](https://github.com/meteorhacks/meteorhacks.github.io/blob/master/_posts/2015-04-22-learn-kubernetes-the-future-of-the-cloud.md) by [Meteorhacks](https://twitter.com/meteorhacks)
* [Kubernetes by Google](http://thevirtualizationguy.wordpress.com/tag/kubernetes/) by [Gaston Pantana](https://twitter.com/GastonPantana)
* [Key Concepts](http://blog.arungupta.me/key-concepts-kubernetes/) by [Arun Gupta](https://twitter.com/arungupta)
* [Application Containers: Kubernetes and Docker from Scratch](http://keithtenzer.com/2015/06/01/application-containers-kubernetes-and-docker-from-scratch/) by [Keith Tenzer](https://twitter.com/keithtenzer)
* [Learn the Kubernetes Key Concepts in 10 Minutes](http://omerio.com/2015/12/18/learn-the-kubernetes-key-concepts-in-10-minutes/) by [Omer Dawelbeit](https://twitter.com/omerio)
* [Top Reasons Businesses Should Move to Kubernetes Now](http://supergiant.io/blog/top-reasons-businesses-should-move-to-kubernetes-now) by [Mike Johnston](https://github.com/gopherstein)
* [The Children's Illustrated Guide to Kubernetes](http://deis.com/blog/2016/kubernetes-illustrated-guide/) by [Deis](https://github.com/deis)
* [The ‘kubectl run’ command](http://medium.com/@mhausenblas/the-kubectl-run-command-27c68de5cb76#.mlwi5an7o) by [Michael Hausenblas](https://twitter.com/mhausenblas)
* [Docker Kubernetes Lab Handbook](https://github.com/xiaopeng163/docker-k8s-lab) by [Peng Xiao](https://twitter.com/xiaopeng163)
* [Curated Resources for Kubernetes](https://hackr.io/tutorials/learn-kubernetes)
* [Kubernetes Comic](https://cloud.google.com/kubernetes-engine/kubernetes-comic/) by [Google Cloud Plaatform](https://cloud.google.com/)
* [Kubernetes 101: Pods, Nodes, Containers, and Clusters](https://medium.com/google-cloud/kubernetes-101-pods-nodes-containers-and-clusters-c1509e409e16) by [Dan Sanche](https://medium.com/@sanche)


Installers
=======================================================================


* [Minikube](https://github.com/kubernetes/minikube) - Run Kubernetes locally :star:9142
* [Kops](https://github.com/kubernetes/kops) - OS Agnostique - AWS - [Apache-2.0](https://github.com/kubernetes/kops/blob/master/LICENSE)
* [Kube-deploy](https://github.com/kubernetes/kube-deploy) :star:490
* [Kubeadm](http://kubernetes.io/docs/admin/kubeadm/) - OS Agnostique - Cloud Agnostique - [Apache-2.0](https://github.com/kubernetes/kubeadm/blob/master/LICENSE)
* [Kubespray](https://github.com/kubernetes-incubator/kubespray) - OS Agnostique - Cloud Agnostique - [Apache-2.0](https://github.com/kubernetes-incubator/kubespray/blob/master/LICENSE)
* [Bootkube](https://github.com/kubernetes-incubator/bootkube) - CoreOS - Cloud Agnostique - [Apache-2.0](https://github.com/kubernetes-incubator/bootkube/blob/master/LICENSE)
* [Kube-aws](https://github.com/coreos/kube-aws) - CoreOS - AWS - [Apache-2.0](https://github.com/coreos/kube-aws/blob/master/CONTRIBUTING.md)
* [Kismatic](https://github.com/apprenda/kismatic) - CentOS - Cloud Agnostique - [Apache-2.0](https://github.com/apprenda/kismatic/blob/master/LICENSE)
* [Juju](https://jujucharms.com/canonical-kubernetes) - Ubuntu - Cloud Agnostique - [Apache-2.0](https://github.com/juju-solutions/bundle-canonical-kubernetes/blob/master/LICENSE)
* [Terraform](https://github.com/kz8s/tack) - CoreOS - AWS - [MIT](https://github.com/kz8s/tack/blob/master/LICENSE)
* [Supergiant](http://supergiant.io/) - CoreOS - Cloud Agnostique - [Apache-2.0](https://github.com/supergiant/supergiant/blob/master/LICENSE)
* [Archon](https://github.com/kubeup/archon) - OS Agnostique - Cloud Agnostique - [Apache-2.0](https://github.com/kubeup/archon/blob/master/LICENSE)
* [KubeNow](https://github.com/kubenow/KubeNow) - Ubuntu - Cloud Agnostique - [Apache-2.0](https://github.com/kubenow/KubeNow/blob/master/LICENSE)
* [Kubicorn](https://github.com/kris-nova/kubicorn) - OS Agnostique - Cloud Agnostique - [Apache-2.0](https://github.com/kris-nova/kubicorn/blob/master/LICENSE)
* [Simplekube](https://github.com/valentin2105/Simplekube) - `systemd` OS - Cloud Agnostique :star:71
* [Conjure-up](https://github.com/conjure-up/conjure-up) - Ubuntu - Cloud Agnostique - [MIT](https://github.com/conjure-up/conjure-up/blob/master/LICENSE)
* [Kube-ansible](https://github.com/kairen/kube-ansible) - OS Agnostique - Cloud Agnostique - [MIT](https://github.com/kairen/kube-ansible/blob/master/LICENSE)
* [Kubernetes-Saltstack](https://github.com/valentin2105/Kubernetes-Saltstack) - `systemD` OS - Cloud Agnostique :star:82
* [matchbox](https://github.com/coreos/matchbox) - CoreOS - Network boot and provision Container Linux clusters (e.g. etcd3, Kubernetes, more). :star:579
* [RKE](https://github.com/rancher/rke) - OS Agnostique - Cloud Agnostique - [Apache-2.0](https://github.com/rancher/rke/blob/master/LICENSE)
* [Typhoon](https://typhoon.psdn.io/) - Container Linux - Cloud Agnostique - [MIT](https://github.com/poseidon/typhoon/blob/master/LICENSE)

Main Resources
=======================================================================

*Official resources from the Kubernetes team*

* [Kubernetes Documentation](https://kubernetes.io/docs/home/)
* [Kubernetes Source](https://github.com/kubernetes/kubernetes/)
* [Kubernetes Troubleshooting](https://kubernetes.io/docs/tasks/debug-application-cluster/troubleshooting/)

Release Notes
=======================================================================

*Official release notes from the Kubernetes team on Stable Kubernetes Releases*

* [Kubernetes-1.10](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG-1.10.md)
* [Kubernetes-1.9](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG-1.9.md)
* [Kubernetes-1.8](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG-1.8.md)
* [Kubernetes-1.7](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG-1.7.md)
* [Kubernetes-1.6](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG-1.6.md)
* [Kubernetes-1.5](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG-1.5.md)
* [Kubernetes-1.4](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG-1.4.md)
* [Kubernetes-1.3](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG-1.3.md)
* [Kubernetes-1.2](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG-1.2.md)


Useful Articles
=======================================================================

*A piece of writing included with others in a newspaper, magazine, or other publication*

* [Installation on Centos 7](http://severalnines.com/blog/installing-kubernetes-cluster-minions-centos7-manage-pods-services)
*  [Packaging Multiple Resources together](http://blog.arungupta.me/kubernetes-application-package-multiple-resources-together/)
*  [An Introduction to Kubernetes](http://www.digitalocean.com/community/tutorials/an-introduction-to-kubernetes) by [Justin Ellingwood](https://twitter.com/jmellingwood)
*  [Scaling Docker with Kubernetes](http://www.infoq.com/articles/scaling-docker-with-kubernetes) by [Carlos Sanchez](https://twitter.com/csanchez)
* [Creating a Kubernetes Cluster to Run Docker Formatted Container Images](http://access.redhat.com/articles/1353773) by [Chris Negus](https://twitter.com/linuxcricket)
* [Containerizing Docker on Kubernetes !!](http://www.linkedin.com/pulse/containerizing-docker-kubernetes-ramit-surana) by [Ramit Surana](https://twitter.com/ramitsurana)
* [Quay: Introducing an Application Registry for Kubernetes](http://coreos.com/blog/quay-application-registry-for-kubernetes.html) by Antoine Legrand
* [Play With Kubernetes Quickly Using Docker](http://zwischenzugs.wordpress.com/2015/04/06/play-with-kubernetes-quickly-using-docker/)
* [1 command to Kubernetes with Docker compose](http://sebgoa.blogspot.in/2015/04/1-command-to-kubernetes-with-docker.html) by [Sebastien Goasguen](https://twitter.com/sebgoa)
* [Nginx Server Deployment using Kubernetes](http://containertutorials.com/get_started_kubernetes/k8s_example.html) by [Rajdeep Dua](https://www.twitter.com/rajdeepdua)
* [What even is a kubelet?](http://kamalmarhubi.com/blog/2015/08/27/what-even-is-a-kubelet/) by [Kamal Marhubi](https://twitter.com/kamalmarhubi)
* [Kubernetes from the ground up: the API server](http://kamalmarhubi.com/blog/2015/09/06/kubernetes-from-the-ground-up-the-api-server/) by [Kamal Marhubi](https://twitter.com/kamalmarhubi)
* [Kubernetes 101 – Networking](http://www.dasblinkenlichten.com/kubernetes-101-networking/) by [Jon Langemak](https://twitter.com/blinken_lichten)
* [Dynamic Kubernetes installation/configuration with SaltStack](http://www.dasblinkenlichten.com/dynamic-kubernetes-installationconfiguration-with-saltstack/) by [Jon Langemak](https://twitter.com/blinken_lichten)
* [Deploying Kubernetes with SaltStack](http://www.dasblinkenlichten.com/deploying-kubernetes-with-saltstack/) by [Jon Langemak](https://twitter.com/blinken_lichten)
* [Logging in Kubernetes with Fluentd and Elasticsearch](http://www.dasblinkenlichten.com/logging-in-kubernetes-with-fluentd-and-elasticsearch/) by [Jon Langemak](https://twitter.com/blinken_lichten)
* [Corekube: Running Kubernetes on CoreOS via OpenStack](http://developer.rackspace.com/blog/running-coreos-and-kubernetes/) by [Mike Metral](https://twitter.com/mikemetral)
* [CoreOS + Kubernetes Step By Step](https://coreos.com/kubernetes/docs/latest/getting-started.html) by [Coreos](https://twitter.com/coreoslinux)
* [Deploying to Kubernetes with Panamax](http://www.ctl.io/developers/blog/post/deploying-to-kubernetes-with-panamax/) by [Brian DeHamer](https://twitter.com/bdehamer)
* [Deploy Kubernetes with a Single Command Using Atomicapp](http://www.projectatomic.io/blog/2015/08/fun-with-kubenetes-and-atomicapp/) by [Jason Brooks](https://twitter.com/jasonbrooks)
* [Deploying a Bare Metal Kubernetes Cluster](http://blog.jameskyle.org/2014/08/deploying-baremetal-kubernetes-cluster/) by [James Kyle](https://twitter.com/jameskyle75)
* [AWS Advent 2014 - CoreOS and Kubernetes on AWS](http://awsadvent.tumblr.com/post/104260597799/aws-advent-2014-coreos-and-kubernetes-on-aws) by [Tim Dsyinger](https://twitter.com/dysinger)
* [Kubernetes and AWS VPC Peering](http://ben.straub.cc/2015/08/19/kubernetes-aws-vpc-peering/) by [Ben Straub](https://twitter.com/benstraub)
* [Deploy a Kubernetes development cluster with Juju!](http://insights.ubuntu.com/2015/07/23/deploy-a-kubernetes-development-cluster-with-juju-2/) by [Matt Bruzek](https://twitter.com/mattatcanonical)
* [Try Kubernetes with Vagrant](http://lollyrock.com/articles/kubernetes-vagrant/) by [Christoph Hartmann](https://twitter.com/chri_hartmann)
* [Keycloak on Kubernetes with OpenShift 3](http://blog.keycloak.org/2015/04/keycloak-on-kubernetes-with-openshift-3.html) by [Marko Strukelj](https://twitter.com/mstruk2000)
* [Kubernetes clusters with Oh-My-Vagrant](http://ttboj.wordpress.com/2015/05/02/kubernetes-clusters-with-oh-my-vagrant/) by [James](https://twitter.com/#!/purpleidea)
* [Fleet Unit Files for Kubernetes on CoreOS](http://blog.michaelhamrah.com/2015/06/fleet-unit-files-for-kubernetes-on-coreos/) by [Michael Hamrah](https://twitter.com/mhamrah)
* [Kubernetes on AWS](http://coreos.com/kubernetes/docs/latest/kubernetes-on-aws.html) by [CoreOS](https://twitter.com/coreoslinux)
* [Testing Kubernetes on AWS](http://alanwill.me/Testing-Kubernetes-on-AWS/) by [Alan Will](https://twitter.com/alanwill)
* [Kubernetes: First steps on Amazon AWS](http://blog.dutchcoders.io/kubernetes-first-steps-on-amazon-aws/) by [Remco](http://blog.dutchcoders.io/author/remco/)
* [Kubernetes Container Orchestration through Java APIs](http://keithtenzer.com/2015/05/04/kubernetes-container-orchestration-through-java-apis/) by [Keith Tenzer](https://twitter.com/keithtenzer)
* [Containers at Scale with Kubernetes on OpenStack](http://keithtenzer.com/2015/04/15/containers-at-scale-with-kubernetes-on-openstack/) by [Keith Tenzer](https://twitter.com/keithtenzer)
* [Installing cAdvisor and Heapster on bare metal Kubernetes](http://www.dasblinkenlichten.com/installing-cadvisor-and-heapster-on-bare-metal-kubernetes/) by [Jon Langemak](https://twitter.com/blinken_lichten)
* [Docker Clustering Tools Compared: Kubernetes vs Docker Swarm](http://technologyconversations.com/2015/11/04/docker-clustering-tools-compared-kubernetes-vs-docker-swarm/)
* [Comparison of Networking Solutions for Kubernetes](http://machinezone.github.io/research/networking-solutions-for-kubernetes/)
* [Why Docker and Google Kubernetes Are Like PaaS Done Right](http://www.sdxcentral.com/articles/news/why-docker-and-google-kubernetes-are-like-paas-done-right/2015/08/)
* [Kubernetes Authentication plugins and kubeconfig](http://www.dasblinkenlichten.com/kubernetes-authentication-plugins-and-kubeconfig/) by [Jon Langemak](https://twitter.com/blinken_lichten)
* [Kubernetes with SaltStack revisited](http://www.dasblinkenlichten.com/kubernetes-with-saltstack-revisited/) by [Jon Langemak](https://twitter.com/blinken_lichten)
* [Kubernetes Authentication - OpenID Connect](http://www.devoperandi.com/kubernetes-authentication-openid-connect/) by [Michael Ward](https://twitter.com/DevoperandI)
* [How to Monitor Kubernetes: A 4-Part Series](http://sysdig.com/blog/monitoring-kubernetes-with-sysdig-cloud/)
* [Logging - Kafka topic by namespace](http://www.devoperandi.com/logging-kafka-topic-by-kubernetes-namespace/) by [Michael Ward](https://twitter.com/DevoperandI)
* [Achieving CI/CD with Kubernetes](http://theremotelab.com/blog/achieving-ci-cd-with-k8s/) by [Ramit Surana](https://twitter.com/ramitsurana)
* [Kubernetes Monitoring Guide](http://www.datadoghq.com/blog/monitoring-kubernetes-era/) by [JM Saponaro](http://github.com/JayJayM)
* [Deploying Kubernetes with Ansible and Terraform](http://solinea.com/blog/deploying-kubernetes-ansible-terraform)
* [Cluster Consul using Kubernetes API](http://www.devoperandi.com/cluster-consul-using-kubernetes-api/)
* [Continuous Deployment with Google Container Engine and Kubernetes](http://semaphoreci.com/community/tutorials/continuous-deployment-with-google-container-engine-and-kubernetes)
* [Handling Sensitive Data In A Docker Application with Kubernetes Secrets](http://scotch.io/tutorials/google-cloud-platform-iii-handling-sensitive-data-in-a-docker-application-with-kubernetes-secrets) by [John Kariuki ](https://twitter.com/_kar_is)
* [How to Create and Use Kubernetes Secrets](http://linoxide.com/containers/create-use-kubernetes-secrets/) by [Mohamed Ez Ez](http://linoxide.com/author/mohamedez/)
* [Microservice Monitoring in Kubernetes with Netsil](http://netsil.com/microservices-monitoring-kubernetes/) by [Matt Baldwin](https://twitter.com/baldwinmathew)
* [Automate deep learning training with Kubernetes GPU-cluster](https://github.com/Langhalsdino/Kubernetes-GPU-Guide) :star:523
* [Kubernetes Production Patterns (and Anti-Patterns)](https://github.com/gravitational/workshop/blob/master/k8sprod.md)
* [Manage Kubernetes Clusters on AWS Using Kops](https://aws.amazon.com/blogs/compute/kubernetes-clusters-aws-kops/)
* [Kubernetes with SaltStack revisited](http://www.dasblinkenlichten.com/kubernetes-with-saltstack-revisited/)
* [Introducing Kubic Project](https://www.suse.com/communities/blog/introducing-kubic-project-new-open-source-project/)
* [Three post learn k8s](http://blog.alexellis.io/tag/learn-k8s/)
* [Kubernetes tips & tricks](http://opsnotice.xyz/kubernetes-tips-tricks/)
* [Jenkins declarative pipelines with Kubernetes](http://radu-matei.com/blog/kubernetes-jenkins-azure/)
* [Kubernetes with OpenStack Cloud Provider: Current state and upcoming changes (part 1 of 2)](http://medium.com/@arthur.souzamiranda/kubernetes-with-openstack-cloud-provider-current-state-and-upcoming-changes-part-1-of-2-48b161ea449a)
* [Choosing a CNI Provider for Kubernetes](http://chrislovecnm.com/kuberentes/cni/choosing-a-cni-provider/?1234) by [Chris Love](https://twitter.com/chrislovecnm)
* [Enable IPv6 on Kubernetes with Project Calico](https://www.projectcalico.org/enable-ipv6-on-kubernetes-with-project-calico/) by [Valentin Ouvrard](https://twitter.com/Valentin_NC)
* [Kubernetes in IPV6-only](https://opsnotice.xyz/kubernetes-ipv6-only/) by [Valentin Ouvrard](https://twitter.com/Valentin_NC)
* [Kubernetes and everything else - Introduction to Kubernetes and it's context](https://rinormaloku.com/introduction-application-architecture/) by [Rinor Maloku](https://twitter.com/rinormaloku)
* [GitOps: High-Velocity CI/CD for Kubernetes](http://dzone.com/articles/gitops-high-velocity-cicd-for-kubernetes)

Managed Kubernetes
=======================================================================

  - [Platform9](http://platform9.com)
  - [Gravitational](http://gravitational.com/)
  - [OpenShift Online](http://www.openshift.com/devpreview/index.html)
  - [Eldarion Cloud](http://eldarion.cloud/)
  - [StackPoint Cloud](http://stackpoint.io/)
  - [Kubermatic](http://www.loodse.com//)
  - [Hasura](https://hasura.io/)
  - [Rancher](https://rancher.com/)


  ### [Developer Platform](#developer-platform)

  - [Fabric8](http://fabric8.io)
   - [Spring Cloud integration](https://github.com/fabric8io/spring-cloud-kubernetes) :star:480
  - [Mantl](https://github.com/mantl/mantl) :star:3027
  - [goPaddle](http://www.gopaddle.io)
  - [VAMP](http://vamp.io)
  - [Draft](https://draft.sh) - a tool for developers to create cloud native applications with Kubernetes


  ### [Enterprise Kubernetes Products](#enterprise-kubernetes-products)

  - [CoreOS Tectonic](http://tectonic.com)
  - [OpenShift - Container Platform](http://www.openshift.com/container-platform/index.html)
  - [SUSE Container as a Service](http://www.suse.com/betaprogram/caasp-beta/)
  - [Kubermatic](http://www.loodse.com/)
  - [Canonical Distribution of Kubernetes - CDK](https://www.ubuntu.com/kubernetes)

  ### [Public/Private Cloud](#publicprivate-cloud)

   - [GKE](https://cloud.google.com/container-engine/) - Google Kubernetes Engine
   - [AWS EKS](https://aws.amazon.com/eks/) - Amazon Elastic Container Service
   - [Azure AKS](https://docs.microsoft.com/en-us/azure/aks/) - Azure Container Service
   - [Vsphere](http://www.vmware.com/products/vsphere.html) - VMWare VSphere
   - [Rackspace](https://www.rackspace.com/en-in) - Rackspace
   - [Alibaba Cloud](https://www.alibabacloud.com/product/kubernetes) - Alibaba Cloud Container Service for Kubernetes

  ### [Paas](#paas)

   *Kubernetes Platform as a Service providers*

  - [Deis Workflow](http://deis.com/) - [Deprecated Public Releases](http://deis.com/blog/2017/deis-workflow-final-release/)
  - [Kel](http://www.kelproject.com)
  - [WSO2](http://wso2.com)
  - [Kumoru](http://medium.com/@kumoru_io) - [Deprecated](https://www.youtube.com/watch?v=_5XQmE7rx9o) - Not Official
  - [Rancher](http://rancher.com/running-kubernetes-aws-rancher/)
  - [OpenShift Origin](http://www.openshift.org/)
  - [Eldarion Cloud](http://eldarion.cloud)
  - [IBM Bluemix Container Service](http://www.ibm.com/cloud-computing/bluemix/containers)
  - [Hasura](http://www.hasura.io)
  - [teresa](https://github.com/luizalabs/teresa) - Simple PAAS that runs on top of Kubernetes. :star:258

Interactive Learning Environments
=======================================================================

*Learn Kubernetes using an interactive environment without requiring downloads or configuration*

* [Katacoda](http://www.katacoda.com/courses/kubernetes)
* [Play with Kubernetes][http://labs.play-with-k8s.com/] - Temporarily Down
* [Kubernetes Bootcamp](http://kubernetesbootcamp.github.io/kubernetes-bootcamp/)


MOOC Courses / Tutorials
=======================================================================

*List of available free online courses([MOOC](https://en.wikipedia.org/wiki/Massive_open_online_course)) and tutorials*

  ### [Courses](#coures)

  - [Scalable Microservices with Kubernetes at Udacity](http://in.udacity.com/course/scalable-microservices-with-kubernetes--ud615)
  - [Introduction to Kubernetes at edX](http://www.edx.org/course/introduction-kubernetes-linuxfoundationx-lfs158x)

  ### [Tutorials](#tutorials)

  - [Kubernetes Tutorials by Kubernetes Team](http://kubernetes.io/docs/tutorials/)
  - [Kubernetes By Example by OpenShift Team](http://kubernetesbyexample.com)
  - [Kubernetes Tutorial by Tutorialspoint](http://www.tutorialspoint.com/kubernetes/)

Case Studies
=======================================================================

*Study of Various different case studies*

* [Building a Bank with Kubernetes](http://monzo.com/blog/2016/09/19/building-a-modern-bank-backend/)
* [Bringing Pokemon Go to Google Cloud](http://cloudplatform.googleblog.com/2016/09/bringing-Pokemon-GO-to-life-on-Google-Cloud.html)
* [Monitoring Kubernetes at Wayblazer](http://sysdig.com/blog/monitoring-docker-kubernetes-wayblazer/)
* [Major League Soccer Monolith to Kubernetes Transition](http://sysdig.com/blog/monoliths-kubernetes-monitoring-transitioning-docker-major-league-soccer/)
* [Using Kubernetes on AWS](https://github.com/hjacobs/kubernetes-on-aws-users) :star:89
* [Kubernetes at Github](http://githubengineering.com/kubernetes-at-github/)
* [Kubernetes the hard way (installation from scratch)](http://github.com/kelseyhightower/kubernetes-the-hard-way/)

Persistent Volume Providers
=======================================================================

*List of some Persistent Volume Providers for Kubernetes.Check out [Persistent Volume Providers](https://github.com/kubernetes/examples/tree/master/staging/persistent-volume-provisioning) for more info*

* [GCE](https://cloud.google.com/compute/)
* [AWS](http://aws.amazon.com)
* [Rook](http://rook.io/)
* [Glusterfs](http://www.gluster.org/)
* [OpenStack Cinder](http://wiki.openstack.org/cinder)
* [CephRBD](http://ceph.com/ceph-storage/block-storage/)
* [QuoByte](http://www.quobyte.com/)
* [Kube-Aliyun](https://github.com/kubeup/kube-aliyun) :star:72
* [Portworx](http://portworx.com/)
* [Rancher Longhorn](https://github.com/rancher/longhorn) :star:294
* [Stork](https://github.com/libopenstorage/stork) :star:73
* [OpenEBS](http://github.com/openebs/openebs/)
* [StorageOS](http://storageos.com)

Developer Libraries/ Scripts
=======================================================================

*List of some libraries & scripts for executions and good referrals*

  ### [Python](#python)

   - [Pykube](https://github.com/kelproject/pykube) :star:302

  ### [Jenkins](#jenkins)

   - [Jenkinsfile with Helm, Go, Docker, Kubectl, JNLP](https://github.com/lachie83/croc-hunter/blob/master/Jenkinsfile)

Projects
=======================================================================

*Kubernetes-related projects that you might find helpful*


## Related Software

*Projects built to make life with Kubernetes even better, more powerful, more scalable*

* [Argo](https://github.com/argoproj/argo) The Workflow Engine for Kubernetes
* [Hypernetes](https://github.com/hyperhq/hypernetes) :star:509
* [Kubernetes Cluster Federation (previously Ubernetes)](https://kubernetes.io/docs/concepts/cluster-administration/federation/)
* [kmachine](https://github.com/skippbox/kmachine) :star:176
* [Kubefuse](http://opencredo.com/introducing-kubefuse-file-system-kubernetes/)
* [KubeSpray](https://github.com/kubespray)
* [Kubernetes Ec2 Autoscaler](https://github.com/openai/kubernetes-ec2-autoscaler) :star:701
* [Kubeform](http://capgemini.github.io/kubeform/)
* [kube-openvpn](https://github.com/pieterlange/kube-openvpn) :star:173
* [Archon](https://github.com/kubeup/archon) :star:169
* [Client Libraries](https://github.com/kubernetes/community/blob/master/contributors/devel/client-libraries.md)
* [Kubic-Project](https://github.com/kubic-project)
* [Telepresence](http://www.telepresence.io) - Locally develop/debug services against a remote Kubernetes cluster
* [Fission Workflows](https://github.com/fission/fission-workflows) - Workflow-based serverless function composition :star:136
* [Ambassador](http://www.getambassador.io) - API Gateway built on the Envoy Proxy

## Package Managers

* [Helm](http://helm.sh)

## Monitoring Services

*To maintain regular surveillance over kubernetes*

* [Console](http://github.com/kubernetes/dashboard) :star:2681
* [Datadog](http://www.datadoghq.com/)
* [eventrouter](https://github.com/heptiolabs/eventrouter) - simple introspective kubernetes service that forwards events to a specified sink. :star:108
* [Grafana Kubernetes App](https://github.com/grafana/kubernetes-app) :star:47
* [Heapster](https://github.com/kubernetes/heapster) :star:2131
* [Kubebox](https://github.com/astefanutti/kubebox) - Terminal console for Kubernetes :star:79
* [Kubedash](https://github.com/kubernetes/kubedash) :star:204
* [Kubernetes Operational View](https://github.com/hjacobs/kube-ops-view) - read-only system dashboard for multiple K8s clusters :star:479
* [Kubetail](https://github.com/johanhaleby/kubetail) :star:664
* [Kubewatch](https://github.com/skippbox/kubewatch) :star:325
* [Netsil](https://github.com/netsil/manifests) :star:58
* [Prometheus](http://prometheus.io)
* [Sysdig Monitoring](https://www.sysdig.com/)
* [Sysdig Open Source](http://www.sysdig.org/)
* [Weave Scope](http://www.weave.works/products/weave-scope/)
* [Searchlight](https://github.com/appscode/searchlight) :star:121
* [Ingress Monitor Controller](https://github.com/stakater/IngressMonitorController) - A Kubernetes Controller to watch your ingresses and create liveness alerts for your endpoints :star:50

## Testing

*Test your applications running on Kubernetes*

* [kube-monkey](https://github.com/asobti/kube-monkey) - Chaos Monkey for Kubernetes clusters :star:716

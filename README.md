# Cloud Partners

There are a large number of ways to deploy DataStax Enterprise and Apache Cassandra.  Finding the best one will involve analysis of your particular environment, balanced against the tools available.  This post is intended as a round up of those tools.  Some are more mature than others, and all are in a state of development and improvement.


DataStax offers three fully supported tools that are maintained by our engineering organization.  These install DataStax Enterprise, our certified, tested and supported version of Apache Cassandra.

Linux Repos — apt and yum
BitRock Installer
OpsCenter Provisioning
In addition, Planet Cassandra has builds of the community version of Apache Cassandra.

The apt-get and yum tools have been wrapped in bash scripts that make them easier to use in clusters.  Scripts to do that are available here:

https://github.com/DSPN/install-datastax
https://github.com/richrein/cassandra.bin
Through our partner collaboration, we also offer tools for deploying on three major cloud platforms.  These make use of apt-get, but also provide cloud specific functionality to help build VMs.

Amazon Web Services
OpsCenter Provisioning
Auto clustering AMI
AWS Whitepaper - Cassandra on AWS
Microsoft Azure
Deployment Guide
Azure Marketplace
Azure Resource Manager
Google Cloud Platform
Cloud Launcher (upcoming)
Google Compute Engine with Deployment Manager
Google Container Engine with Deployment Manager
Deployment Guide
Deployment Guide - manual using gcloud cli
Cassandra Bitnami Offer
We are also working in the container space to improve support there.

Docker Whitepaper
Docker Scripts
In addition, there are a variety of Apache Cassandra resources.  These include:

Cassandra Dockerhub Image
Kubernetes Cassandra Example
Mesos DCOS Cassandra
There are also a variety of provisioning scripts that may be helpful.  These include:

Chef
Target DSE Cookbook
Pivotal DSE Chef
Puppet
Official Puppet Cassandra
Unofficial DSE - https://github.com/oaeproject/puppet-hilary/tree/master/modules/dse
Unofficial DSE - https://github.com/justinleveck/boxci-dse-cassandra-puppet
A variety of other provisioning resources are:

Rackspace
Pivotal CloudFoundry Tile
Century Link
I hope you find these links helpful.  If there are resources you’ve found valuable which I’ve missed, please let me know and we can add them in.  Additionally, if there are provisioning scenarios we should support that we don’t, I’d love to learn more about what you need.  I’m available on twitter @benofben or via email at ben.lackey@datastax.com.
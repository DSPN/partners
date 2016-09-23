# Cloud Partners

There are a large number of ways to deploy DataStax Enterprise and Apache Cassandra.  Finding the best one will involve analysis of your particular environment, balanced against the tools available.  This post is intended as a round up of those tools.  Some are more mature than others, and all are in a state of development and improvement.

## Provisioning DataStax

DataStax offers three fully supported tools that are maintained by our engineering organization.  These install DataStax Enterprise, our certified, tested and supported version of Apache Cassandra.

* Linux Repos — apt and yum
* BitRock Installer
* OpsCenter Lifecycle Manager
* In addition, Planet Cassandra has builds of the community version of Apache Cassandra.

Through our partner collaboration, we offer tools for deploying on major cloud platforms.  

## Cloud
* [Amazon Web Services](Amazon%20Web%20Services.md)
* [Microsoft Azure](Microsoft%20Azure.md)
* [Google Cloud Platform](Google%20Cloud%20Platform.md)
* [Oracle Cloud](Oracle%20Cloud.md)

## Other Technologies
* [Pivotal Cloud Foundry](Pivotal%20Cloud%20Foundry.md)
* Chef
- Target DSE Cookbook
- Pivotal DSE Chef
* Puppet
- Official Puppet Cassandra
- Unofficial DSE - https://github.com/oaeproject/puppet-hilary/tree/master/modules/dse
- Unofficial DSE - https://github.com/justinleveck/boxci-dse-cassandra-puppet
* [Containers](Containers.md)
* Rackspace

I hope you find these links helpful.  If there are resources you’ve found valuable which we've missed please submit a pull request.

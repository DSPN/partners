# Cloud Partners

There are a large number of ways to deploy DataStax Enterprise and Apache Cassandra.  Finding the best one will involve analysis of your particular environment, balanced against the tools available.  This repo is intended as a round up of those tools.  Some are more mature than others, and all are in a state of development and improvement.

## Provisioning DataStax

DataStax offers three fully supported tools that are maintained by our engineering organization.  These install DataStax Enterprise, our certified, tested and supported version of Apache Cassandra.  Two of those tools are:

* Linux Repos — apt and yum
* BitRock Installer

Those are detailed [here](http://docs.datastax.com/en/latest-dse/datastax_enterprise/install/installTOC.html).

[OpsCenter Lifecycle Manager](https://docs.datastax.com/en/latest-opsc/opsc/LCM/opscLCMOverview.html) provides a graphical way to provision clusters on top of existing IaaS

In addition, [Planet Cassandra](http://www.planetcassandra.org/) has builds of the community version of Apache Cassandra.

Through our partner collaboration, we offer tools for deploying on major cloud platforms.  

## Cloud
* [Amazon Web Services](Amazon%20Web%20Services.md)
* [Microsoft Azure](Microsoft%20Azure.md)
* [Google Cloud Platform](Google%20Cloud%20Platform.md)
* [Oracle Cloud](Oracle%20Cloud.md)
* [Century Link](https://academy.datastax.com/resources/getting-started-datastax-enterprise-centurylink-cloud)

## Other Technologies
* [Pivotal Cloud Foundry](Pivotal%20Cloud%20Foundry.md)
* Containers
    * [Mesos](Mesos.md)
    * [Kubernetes](Kubernetes.md)
    * [Docker](Docker.md)
* [Chef](Chef.md)
* [Puppet](Puppet.md)
* Rackspace
    * https://marketplace.rackspace.com/apps/909
* Datapipe
    * Deploying DataStax Enterprise on Datapipe Cloud Provider - https://academy.datastax.com/units/deploying-datastax-enterprise-datapipe-cloud-provider

We hope you find these links helpful.  If there are resources you’ve found valuable which we've missed please submit a pull request.

# Using Anchore with JFrog Artifactory

This document will walk through integrating Anchore with jFrog Artifactory. 

## Prerequisites

- Access to an installed Anchore Engine or Enterprise instance
- JFrog Artifactory installed
- Docker registry configured in Artifactory

### Configuring Anchore access to the Artifactory Docker Registry

#### Anchore Enterprise UI

Navigate to the configure tab within the UI, select registries, and click 'Add New Registry'

Fill in the following fields: 

![anchore-registry](images/anchore-ui-registry.png)

**Note:** To find the hostname of your Artifactory registry, you can select set me up in the UI and you will see the following popup:

In this example, we can see the hostname for this registry is *anchoredemo-docker.jfrog.io*

![jfrog-registry](images/artifactory-registry-info.png)
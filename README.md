
**

## Take-on Helm Charts

**

This repository contains a combined helm chart for 5 of our services that you can deploy using Helm.

These services are:

-   Database Layer
-   Persistence Layer
-   Validation Persistence Layer
-   Business Logic Layer
-   UI Layer

**Installing the Chart from Git Repo**

    $ helm install -n ./takeon-chart/

**Installing the Chart from the package**

    $ helm install takeon-chart-0.0.1.tgz --debug

**To list all releases on the Cluster**

    $ helm list

**Uninstalling the Chart**

    $ helm delete or $ helm del --purge


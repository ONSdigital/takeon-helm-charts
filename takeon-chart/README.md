
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

**Installing the Chart**

    $ helm install -n ./takeon-chart/

**To list all releases on the Cluster**

    $ helm list

**Uninstalling the Chart**

    $ helm delete or $ helm del --purge


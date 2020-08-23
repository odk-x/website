---
title: Software
permalink: /software/
sidebar:
  nav: "software"
---

The current and previous releases of ODK-X (formerly ODK 2) tools are hosted on GitHub in each tool's repository.

The tools are generally updated every month, so stay up to date by watching the [releases](https://forum.odk-x.org/c/releases) category on the forum.

## [ODK-X Tables](#odk-x-tables)
A mobile data curation Android app that enables users to see previously collected data and make updates using defined workflows. Tables requires ODK-X Services.

Download [Tables releases on GitHub](https://github.com/odk-x/tables/releases)

[Source Code](https://github.com/odk-x/tables)

## [ODK-X Survey](#odk-x-survey)
A question based data collection Android app that uses a predefined survey specified using the XLSXConverter (part of Application Designer). Survey requires ODK-X Services.

Download [Survey releases on GitHub](https://github.com/odk-x/survey/releases)

[Source Code](https://github.com/odk-x/survey)

## [ODK-X Services](#odk-x-services)
An Android app that handles database access, file access, and data synchronization services with an ODK-X Cloud Endpoint.

Download [Services releases on GitHub](https://github.com/odk-x/services/releases)

[Source Code](https://github.com/odk-x/services)

## [ODK-X Application Designer](#odk-x-application-designer)
A Windows/macOS/Linux design environment that runs in Chrome for creating, customizing, and previewing your forms that will render on Survey. 

Download [Application Designer releases on GitHub](https://github.com/odk-x/app-designer/releases)

[Source Code](https://github.com/odk-x/app-designer)

## [ODK-X Suitcase](#odk-x-suitcase)
A Windows/macOS/Linux tool for synchronizing data from an ODK-X Cloud Endpoint into an exported CSV file.

Download [Suitcase releases on GitHub](https://github.com/odk-x/suitcase/releases)

[Source Code](https://github.com/odk-x/suitcase)

## [ODK-X Sync Endpoint](#odk-x-sync-endpoint)
Sync Endpoint is a server that enables data to replicated between mobile devices. Sync Endpoint runs in Docker and provides additional micro-services for authentication management. Requires [Docker](https://docs.docker.com/install/) and [Swarm](https://docs.docker.com/engine/swarm/swarm-tutorial/create-swarm/).

To build the image run the following command (you could also clone the repository and build it locally): 
```
docker build --pull -t <orgname>/sync_endpoint https://github.com/odk-x/sync-endpoint-containers.git
```

For more detailed information and alternative Cloud Endpoints refer to the [documentation](https://docs.odk-x.org/cloud-endpoints-intro/) 

The source code for each of the Sync Endpoint services are available in these repositories:

- [Sync Endpoint](https://github.com/odk-x/sync-endpoint)
- [Sync Endpoint Containers](https://github.com/odk-x/sync-endpoint-containers)
- [Sync Endpoint Web UI](https://github.com/odk-x/sync-endpoint-web-ui)
- [Sync Endpoint Default Setup](https://github.com/odk-x/sync-endpoint-default-setup)

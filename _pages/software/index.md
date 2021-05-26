---
title: Software
permalink: /software/
sidebar:
  nav: "software"
---

The current and previous releases of ODK-X (formerly ODK 2) tools are hosted on GitHub in each tool's repository.

The tools are generally updated every three to four months, so stay up to date by watching the [releases](https://forum.odk-x.org/c/releases) category on the forum.

## [ODK-X Tables](#odk-x-tables)
A mobile data curation Android app that  allows users to visualize and update existing data.
Tables also enables web developers to build powerful data management applications to handle their complex workflows. Tables gives you the flexibility to implement your own arbitrary complex workflow. For example you might collect data via a customized mapping interface: Tables allows you to build an application using web technologies to achieve that.

Download [Tables releases on GitHub](https://github.com/odk-x/tables/releases)

[Source Code](https://github.com/odk-x/tables)

## [ODK-X Survey](#odk-x-survey)
A question based data collection Android app that uses a predefined survey specified using the XLSXConverter (part of Application Designer). It operates similarly to ODK Collect, but is based on HTML, CSS, and Javascript rather than native Android, and is more flexible in its presentation and execution.

Download [Survey releases on GitHub](https://github.com/odk-x/survey/releases)

[Source Code](https://github.com/odk-x/survey)

## [ODK-X Services](#odk-x-services)
An Android app that handles database access, file access, and data synchronization services between all the ODK-X applications. Mostly this happens behind the scenes, but you will need to install ODK-X Services as a prerequisite to using the other ODK-X tools. It also allows you to sync data collected by the ODK-X tools with an ODK-X Cloud Endpoint. 

Download [Services releases on GitHub](https://github.com/odk-x/services/releases)

[Source Code](https://github.com/odk-x/services)

## [ODK-X Application Designer](#odk-x-application-designer)
ODK-X Application Designer is a tool to help you design data management applications on top of the ODK-X framework. It works in a Windows/macOS/Linux design environment in conjunction with Excel or OpenOffice for form design, the Chrome browser for rendering, and your favorite editor for template design.

Download [Application Designer releases on GitHub](https://github.com/odk-x/app-designer/releases)

[Source Code](https://github.com/odk-x/app-designer)

## [ODK-X Suitcase](#odk-x-suitcase)
A Windows/macOS/Linux tool for synchronizing data from an ODK-X Cloud Endpoint. ODK-X Suitcase provides access to data on an ODK-X Cloud Endpoint from a personal computer. 
Data downloaded from an ODK-X Cloud Endpoints is stored as spreadsheets in CSV format. This format is compatible with most spreadsheet software, for example Excel or Numbers. Once downloaded, the spreadsheets will be available for offline viewing. Similarly, data to be uploaded to an ODK-X Cloud Endpoint with ODK-X Suitcase must be stored in a properly formatted csv file.

Download [Suitcase releases on GitHub](https://github.com/odk-x/suitcase/releases)

[Source Code](https://github.com/odk-x/suitcase)

## [ODK-X Sync Endpoint](#odk-x-sync-endpoint)
Sync Endpoint is a server that enables data to replicated between mobile devices. It communicates with your ODK-X Android applications to synchronize your data and application files.
Depending on your needs, ODK-X Sync Endpoint can either be installed in a cloud-based virtual machine, or on your own infrastructure.

For more detailed information and alternative Cloud Endpoints refer to the [documentation](https://docs.odk-x.org/cloud-endpoints-intro/) 

The source code for each of the Sync Endpoint services are available in these repositories:

- [Sync Endpoint](https://github.com/odk-x/sync-endpoint)
- [Sync Endpoint Containers](https://github.com/odk-x/sync-endpoint-containers)
- [Sync Endpoint Web UI](https://github.com/odk-x/sync-endpoint-web-ui)
- [Sync Endpoint Default Setup](https://github.com/odk-x/sync-endpoint-default-setup)

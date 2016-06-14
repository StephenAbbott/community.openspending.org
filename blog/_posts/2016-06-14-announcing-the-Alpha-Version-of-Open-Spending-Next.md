---
title: "Announcing the Alpha Version of Open Spending Next"
authors:
- The Open Spending Team
---

We’re happy to announce that a new, improved version of Open Spending is now being launched as an Alpha Version. Open Spending Next provides a set of tools enabling users to visualise, analyse and publish budget and spending data against an Open Fiscal Data standard.

Open Spending Next is designed, developed and maintained by Open Knowledge International and, as an open source project, also reflects the very valuable contributions of an active, passionate and committed [community](http://community.openspending.org/next/).

Open Spending Next fills a gap in the lack of open tools that offer easy budget data publication, visualisation and analytics for individuals and organisations working with fiscal data, but also this time, provides a data model standard.

The aim of the project is to support the international open data community by offering a platform that makes it easier for civil society organisations, activists and journalists to see how and where public money is being spent. Open Spending is also targeted to governments and any regional, local administration or municipality level to increase fiscal transparency.

The Fiscal Data Package Standard unveils spending data and fiscal documents at all stages of the budget process by defining a common data model.

Open Spending Next Alpha Release comes with 3 core tools and a fully working API:

* **The OS Packager** that enables users to map any fiscal data against the standard, and create a Fiscal Data Package from CSV files with a simplified workflow. This package can be  uploaded to OpenSpending API with just a few clicks..
* **The OS Viewer** lets users create and customise visualisations based on their budget and spending data. Treemaps, pie charts, bar charts, geolocation, line charts, tables, you name it!

Technically speaking, the whole Viewer can be embedded in 3rd party apps, as well as each visualisations. The view components use a refactored codebase of [Babbage.UI](https://github.com/openspending/babbage.ui) by **[Friedrich Linderberg](http://pudo.org/)**. See [Spend DB <3 Open Spending blog post](http://community.openspending.org/blog/2015/11/30/openspending-next-spendb/) and include some new views like a GeoView. Next on the list is the integration of a Sankey diagram!

* **The OS DataMine**: A rich analytical tool based on [re:dash](http://redash.io/) that will help perform deep queries into fiscal data.

* **The API**: This V3 API is almost entirely based on the excellent [Babbage](https://github.com/openspending/babbage). This API also features a fully backwards compatible implementation of the OpenSpending V2 API for legacy apps that depend on it.

![OS-Next](https://blog.okfn.org/wp-content/uploads/2016/06/Capture-d’écran-2016-06-13-à-17.40.16-1024x626.png "OpenSpending Next")

Since we started developing OS Next, we’ve been working in the following general areas:

* Collaborating with our partners [GIFT](http://www.fiscaltransparency.net/) and the [BOOST World Bank team](http://wbi.worldbank.org/boost/boost-initiative) to develop the [Fiscal Data Package](http://fiscal.dataprotocols.org/spec/). We’ve trialled and integrated datasets from different Boost countries with the Fiscal Data Package such as [Moldova](http://next.openspending.org/viewer/boost:boost-moldova-2005-2014?measure=adjusted.sum&order=adjusted.sum%7Cdesc&visualizations%5B%5D=Treemap&groups%5B%5D=location_2.location), [Tunisia](http://next.openspending.org/viewer/boost:boost-tunisia-2008-2014?measure=PAYE.sum&order=PAYE.sum%7Cdesc&visualizations%5B%5D=Treemap&groups%5B%5D=administrative_classification_2.ADMIN1&rows%5B%5D=activity_2.PROG&columns%5B%5D=date_2.YEAR) or [Peru](http://next.openspending.org/viewer/boost:boost-peru-2012-2014?measure=Executed.sum&order=Executed.sum%7Cdesc&visualizations%5B%5D=Treemap&groups%5B%5D=functional_classification_2.Function1&rows%5B%5D=activity_Program1.Program1&columns%5B%5D=date_2.Year).
* Collaborating in the [OpenBudgets.eu](http://openbudgets.eu/) project consortium together with [Open Knowledge Germany](https://okfn.de/), Open Knowledge Greece , [J++](http://www.jplusplus.org/en), [Transparency International EU](http://www.transparencyinternational.eu/), [University of Prague](http://www.vse.cz/) and [University of Bonn](https://www.uni-bonn.de/) to build a platform that improves transparency and opens the black box of European structural funds spending data. Read about our latest news and research topics at http://openbudgets.eu/blog/.

**How can you contribute to Open Spending?**

There are so many ways to contribute to Open Spending!

OpenSpending is guided by community principles. Anyone interested in financial data can contribute. We’re friendly to newcomers and old hands alike – everyone was new once, and we value all levels of experience.

Do you have an experience working with budget data? Don’t wait any longer and start using the tool, we would welcome any feedback about your impressions on the new version and how it can be improved to serve your needs.

If you’re a budget activist – look at the available data and upload the newest data for your country or municipality, in order to make it available for the larger community.

Do you run a budget data or fiscal transparency portals ?  You will be able to use Open Spending data visualizations and embed them in your portal.

Are you a government representative? We can’t wait for you to adopt the Fiscal Data Package as an international standard.

Are you a software developer, a data scientist or analyst? Do you have knowledge in data visualisation, data architecture, play with Python or D3? We are open to your suggestions and contributions, don’t wait any longer and take a look at the technical documentation > http://docs.openspending.org/en/latest/developers/

All material created within the project is open data and open content built with open tools.

## How to reach us?
Nothing is more easy to contact us and get in touch, the team is available via these channels:

1. In the [OpenSpending discussion forum](https://discuss.okfn.org/c/openspending)
2. On Gitter.im in the [OpenSpending chat room](https://gitter.im/openspending/chat)
3. On the [OpenSpending issue tracker](https://github.com/openspending/openspending/issues)

Expect a lot of bugs, and a lot of updates and stories!  But for now, we can’t wait to get your feedback! [START / DISCOVER](http://next.openspending.org/)! 
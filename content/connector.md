---
order: 5
date: 2019-08-19
slug: about-connector
title: WDFN Tableau Data Connector
categories:
  - Web Data Connector
type: post
description: The Water Data for the Nation (WDFN) Tableau Web Data Connector (WDC) is designed for users of the Tableau software who want to seamlessly integrate USGS Water data into their analytics operations. 
thumbnail_path: "/static/tableau-connector/tableau_connector.png"
thumbnail_alt: "Screenshot of a portion of the Tableau Data Connector, showing boxes for selecting paramaeters and parameter groups."
keywords:
  - Tableau
  - Web
  - Data
  - Connector
containerclass: grid-container
---



The [Water Data for the Nation (WDFN) Tableau Web Data Connector (WDC)](/tableau-connector/) is designed for users of the Tableau software who want to seamlessly integrate USGS Water data into their analytics operations. This system is open to the public, and is currently configured for the [waterservices.usgs.gov instantaneous values (IV) service](https://waterservices.usgs.gov/rest/IV-Service.html).

The WDFN WDC system provides USGS Water data and an accompanying Tableau schema for each parameter for each site, including geographic coordinates and datetimes for each observation. When invoking this system through the Tableau web data connector option, the JSON data from the WDFN IV web services is automatically loaded into Tableau in the format specified by the generated schema.

This system requires a desktop Tableau client. To use this system, first install a Tableau desktop client on your PC then enter the URL for this page under the web data connector option in the connect menu. Details of the constraints imposed by the database that feeds this tool are available here.

This WDC is in the early stages of development and testing, and we want to hear from you about how it works. Please [contact us](https://water.usgs.gov/contact/gsanswers?pemail=gs-w_water_data_for_the_nation&subject=Water%20Data%20for%20the%20Nation%20Labs%20Feedback&viewnote=%3CH1%3EUSGS+WDFN+Tableau+Connector+Feedback%3C/H1%3E) with questions or comments. Bug reports and feature requests can be submitted to the WDFN development team as "issues" [at the Github repository for the project.](https://github.com/usgs/nwisweb-tableau-data-connector/issues)

Any use of trade, firm, or product names is for descriptive purposes only and does not imply endorsement by the U.S. Government

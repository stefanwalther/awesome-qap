[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome resources related to several Qlik Sense integration resp. Qlik Analytics Platform (QAP) topics. Inspired by [awesome lists](https://github.com/sindresorhus/awesome).
Contributions are not only always welcome but the entire idea behind this list!
Please take a look at the [contribution guidelines and quality standard](CONTRIBUTING.md) page first.

- [Integration Overview](#integration-overview)
- [Solutions built on top of QAP](#solutions)
	- [On Demand App Generation](#on-demand-app-generation)
- [Engine API](#engine-api)
- [Mashup API](#mashup-api)
- [Visualization API](#visualization-api)
- [Widget Libraries](#widget-libraries)
- [Capability APIs](#capability-apis)
- [Building Visualization Extensions](#building-visualization-extensions)
- [Visualization Extensions](#visualization-extensions)
- [Qlik Sense Repository (QRS) API](#qlik-sense-repository-api)
- [Security](#security)
- [Connectivity](#connectivity)
- [DevOps](#devops)
- [.NET SDK](#net-sdk)
- [Qlik Sense QMC Utilities](#qliksense-qmc-utilities)

---

## Integration Overview

- [Qlik Analytics Platform / QAP](http://help.qlik.com/en-US/sense-developer/2.2/Subsystems/Platform/Content/Architecture/qlik-analytic-platform.htm) - Overview of the Qlik Analytics Platform

## Solutions
Solutions built on top of Qlik Analytics Platform / leveraging APIs of QAP:

- [Fasttrack](https://github.com/jacobvinzent/Fasttrack) - Transfer dimensions and expressions from QlikView 11 to Qlik Sense
- [QLIK-Visualization-API-json-file](https://github.com/jacobvinzent/QLIK-Visualization-API-json-file) -  Reuse your application design done in the Qlik Sense Desktop or on the Qlik Enterprise server across multiple applications for different customers
- [SaaS Demo](https://github.com/QHose/QRSMeteor) - SaaS API automation demo.
- [mdemo](https://github.com/aalteirac/mdemo) - A Qlik Sense Mashups demo Extension for Qlik Sense Desktop and Qlik Sense Server.

### On Demand App generation

- [On demand app generation](https://github.com/websy85/on-demand-app-gen) - A simple On-demand app generation extension for Qlik Sense.
- [app-on-demand](https://github.com/bardess/app-on-demand) - On demand app generation
- [architeqt](https://github.com/mindspank/architeqt) - Generated Qlik Sense apps from a template
- [qlik-elastic](https://github.com/pouc/qlik-elastic) - Generated Qlik Sense apps from ElasticSearch
- [QlikSocial](https://github.com/johsund/QlikSocial) - Social Media on demand app generator for Qlik Sense
- [Qlik Data Concierge](https://github.com/QlikPreSalesDACH/Qlik-Data-Concierge) - A self-service solution for non-technical BEx users based on Qlik Sense

## Engine API

- [Introduction to Generic Object](https://community.qlik.com/docs/DOC-7732) - Very detailed explanation of the Generic Object, which is the foundation for all visualizations in Qlik Sense.
- [qsocks](https://github.com/mindspank/qsocks) - A lightweight promise wrapper around the Qlik Sense Engine API.
- [Engine API Explorer](http://qliksite.io/qlik-sense/introducing-engine-api-explorer/) - Introduction to the Engine API Explorer (a part of Dev Hub).
- [Engine API and qSocks](https://community.qlik.com/blogs/qlikviewdesignblog/2015/07/20/engine-api-and-qsocks-connecting-and-getting-a-list-of-available-apps) - Engine API and qSocks - Connecting and getting a list of available apps.
- [QlikSenseAngularDemo](https://github.com/thomasfriebel/QlikSenseAngularDemo) - A lightweight browser demo of the new Qlik Engine API.
- [Qlik REST In Sense (otto)](https://github.com/ralfbecher/q-risotto) - A RESTful Engine API wrapper to easily accessapps, objects and its data on a Qlik Sense server thru a REST API to integrate with other systems.
- [QIX Struct Generator](http://opensrc.axisgroup.com/qix-struct-generator/) - QIX Engine Struct Generator.

## Mashup API

- [Mashup API Tutorials](https://community.qlik.com/thread/140982) - Great series of tutorials how to get started with Mashups.
- [Extensions to the Mashup API](https://github.com/websy85/extended-mashup-api)
- [Qlik Analytics for Visual Studio](https://visualstudiogallery.msdn.microsoft.com/de8d2bfa-fd5e-44d5-ab23-f8bccdcc2ef0) - Visual Studio plugin to integrate Qlik Sense visualizations into an existing web site.

## Visualization API

- [The Visualization API - An Overview](https://community.qlik.com/docs/DOC-16768) - Great overview of the Visualization API, created by Erik Wetterberg.
- Some great gists, using the Visualization API:
    - [Basic Visualization API example.](https://jsfiddle.net/mindspank/803627ug/) - Connecting to Qlik Sense and displaying fully interactive graphs based on Qlik data.
    - [Patching properties on the fly](https://jsfiddle.net/mindspank/b6zob8ku/) -
    - [Selective Data points](https://jsfiddle.net/mindspank/1zqp7zuc/) -
    - [Visualization API and Extensions on the fly](https://jsfiddle.net/mindspank/rnmka3zh/) - Loading on the fly extensions and using the visualization api to display them.
- [Introduction to Generic Object](https://community.qlik.com/docs/DOC-7732) - Very detailed explanation of the Generic Object, which is the foundation for all visualizations in Qlik Sense.

## Widget Libraries
Some collections of Widgets:

- [SenseUI-Widgets](https://github.com/yianni-ververis/SenseUI-WidgetLibrary) - The Widget library created by Qlik's demo team.
- [Themed Widgets](https://github.com/newmans99/Themed-Widgets) - Qlik Sense UI Widgets supporting themes

## Capability APIs

- [WebPack-CapabilityAPIs](https://github.com/mindspank/webpack-capabilitiesapi) - Examples how to use the Capability APIs in combination with WebPack    

## Building Visualization Extensions

- [Qlik Sense Extension Tutorial](https://github.com/stefanwalther/qliksense-extension-tutorial) - Living tutorial on how to create visualization extensions, including sample code.
- [Qlik Sense Extension with D3](http://blog.axc.net/tutorial-how-to-build-a-qlik-sense-extension-with-d3/) - Tutorial: How to Build a Qlik Sense Extension with D3.
- [D3 & Visualization Extensions](https://community.qlik.com/docs/DOC-16346) - Tutorial on using D3 in Qlik Sense Visualization Extensions
- [Using Bootstrap CSS in Qlik Sense Visualization Extensions](http://qliksite.io/qlik-sense/using-bootstrap-css-qliksense-visualization-extensions/) - How to prevent clashes between Qlik Sense' CSS files and those from Bootstrap.
- [Lasso filtering](http://blog.axc.net/lasso-filtering-in-qlik-sense-extensions/) - Lasso filtering in Qlik Sense Visualization Extensions.
- [Lasso plugin](https://github.com/skokenes/D3-Lasso-Plugin) - D3 plugin, very similar to the lasso in Qlik Sense.
- [Qlik-Sense-D3-Visualization-Library](https://github.com/skokenes/Qlik-Sense-D3-Visualization-Library) - A library of d3 visualizations housed in 1 Qlik Sense extension.
- [ES6, Babel, Webpack & GulpJS](https://github.com/alner/NewQlikSenseVisualizationTemplate) - Template for developing visualization extensions, using ES6, Babel, Webpack & GulpJS).

## Visualization Extensions
A random selection of visualization extensions, you'lll find much more on [branch](http://branch.qlik.com).

- [Google Annotation Chart](https://github.com/yianni-ververis/google-annotation-chart)
- [qse-mgoimagegrid](https://github.com/murraygm/qse-mgoimagegrid) - Display images in a grid.
- [SenseDateRangePicker](https://github.com/NOD507/SenseDateRangePicker) - Sense Date Range Picker
- [Waterfall extension](https://github.com/NielsLindberg/Qliksense.Extension.amWaterfall) - Waterfall extension based on amCharts.
- [xGridResizer](https://github.com/ludberg/xGridResizer) - This extension lets you resize the grid of a sheet in Qlik Sense. (Attention: absolutely not supported and very experimental)
- [xTableBox](https://github.com/ludberg/xTableBox) - Display all columns of a table, very usefull during the data-modelling process.

## Qlik Sense Repository API

- [Qlik-Cli](https://github.com/ahaydon/Qlik-Cli) - PowerShell Cmdlets to talk to the QRS API.
- [QlikSensePowerShell](https://github.com/JoeBickley/QlikSensePowerShell) - A powershell plugin with common Qlik Sense automation functions.

## Security

- [Authenticating with certificates](http://qliksite.io/qlik-sense/authentication-certificates/) - A step-by-step guide how to set up, configure and use certificates for authentication.
- [AccessControlTestModule](https://github.com/flautrup/AccessControlTestModule) - Authentication module for Qlik Sense to be used to test Access Control
- [Using Header Authentication](http://qliksite.io/qlik-sense/header-authentication-configuration/) - A step-by-step guide how to set up and use header authentication.
- [qlik-auth](https://github.com/braathen/qlik-auth) - Node.js library to simplify custom authentication with both QlikView and Qlik Sense.
- [qlik-auth-net](https://github.com/braathen/qlik-auth-net) - Asp.net module for simplifying custom authentication with Qlik Sense.
- [qlik-auth-google](https://github.com/braathen/qlik-auth-google) - Qlik Sense OAuth2 authentication module designed specifically for Google services.
- [qlikoauth](https://github.com/braathen/qlikoauth) - Demonstration using OAuth 2.0 for QlikView and Qlik Sense integration.
- [Chrome Security Rule Management](https://github.com/flautrup/ChromeRuleManagement) - Chrome app developed to help the reuse and transfer of rules between Qlik Sense environments.
- [Using Capability APIs with tickets](https://github.com/mindspank/express-qps-sample) - Example how to use [Express](http://expressjs.com/) to host a page using the Capabilities API from Qlik Sense.

## Connectivity

- [Butler for Qlik Sense](https://github.com/mountaindude/qlik-sense-butler) - Connectivity proxy for Sense, features such as posting to Slack from load script, real-time forwarding of reload failures and user login/logout events to Slack and MQTT, and others.  
- [Butler MQTT](https://github.com/mountaindude/butler-mqtt) - Slimmed down version of Butler, only including the REST-to-MQTT bridge. useful for creating real-time script reload dashboards.

## DevOps

- [SenseOps](https://senseops.rocks) - Qlik Sense + DevOps = SenseOps. Thoughts on best practices for using Sense in the enterprise.
- [Butler SOS](https://github.com/mountaindude/butler-sos) - Grafana powered real-time operational dashboards for Qlik Sense enterprise.

## .NET SDK

- [.NET SDK Examples](https://github.com/AptkQlik/PublicExamples) - Some examples using the .NET SDK.
- [Reloader NTLM](https://github.com/AptkQlik/Reloader_NTLM) - Example how to avoid consuming license tokens and how to use other credentials than the logged on user.
- [SDKConnectionWithSenseTicket](https://github.com/AptkQlik/SDKConnectionWithSenseTicket) - Connect with the Qlik Sense .Net SDK using an existing session.
- [ScriptReloader](https://github.com/AptkQlik/ScriptReloader) - Illustrate how one can decompose a Qlik Sense App so that scripts can be reloaded from an external server.
- [QlikSenseScriptObfuscater](https://github.com/AptkQlik/QlikSenseScriptObfuscater) - A way to hide scripts with .Net SDK in Qlik Sense.

## Qlik Sense QMC Utilities

A collection of management console utilities for use with Qlik Sense.

- [App Meta Fetcher](https://github.com/eapowertools/qmcu-app-meta-fetcher) - App Meta Fetcher is used in conjunction with the Governed Metrics Application (included in the Governed Metrics Service installation). This plugin outputs Site-level application metadata into a collection of csv files which can be used to identify application, master and non-master item, visualization, and sheet metadata.
- [App Mover](https://github.com/eapowertools/qmcu-app-mover) - App Mover is a tool to help administer application movement from site to site. It allows exporting from one Qlik Sense environment and importing into 1 or many Qlik Sense environments.
- [App Object Approver](https://github.com/eapowertools/qmcu-appobject-approver) - The App Object Approver enables approval of published sheets, stories, bookmarks, dimensions, measures, and Master Items in an app, thus, making them base objects of the Qlik Sense application. In addition, it's possible to un-approve objects as well and push them back to the community.
- [Custom Property Bulk Loader](https://github.com/eapowertools/qmcu-custom-prop-loader) - The Custom Property Bulk Loader enables administrators to upload a list of values for managing custom properties without having to enter values manually. The bulk loader is able to update existing custom properties, or create new custom properties for a Qlik Sense deployment. Select a custom property or provide a name, select the resources the custom property will apply to, and upload a csv file with a single column list of values. Once that's done click the Create or Update button and to add or modify the custom property.
- [Real QMC](https://github.com/eapowertools/qmcu-real-qmc) - The Actual Qlik Management Console in QMC Utilities
- [Security Rule Manager](https://github.com/eapowertools/qmcu-rule-manager) - The Security Rule Manager allows a Qlik Sense administrator to export and import security rules from the Qlik Sense repository. This is helpful if you have developed a security model in one environment and would like to bring the whole model (or even specific security rules) over to a different environment.
- [Source Control Assistant](https://github.com/eapowertools/qmcu-sclite) - The Source Control Assistant is an application backup and restore solution for Qlik Sense.  Apps are serialized to json files, which can be easily stored and versioned in popular source control systems like Subversion, TFS, and Github.

# License

[![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

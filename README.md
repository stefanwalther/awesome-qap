[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome resources related to several Qlik Sense integration resp. Qlik Analytics Platform (QAP) topics. Inspired by [awesome lists](https://github.com/sindresorhus/awesome).
Contributions are not only always welcome but the entire idea behind this list!
Please take a look at the [contribution guidelines and quality standard](CONTRIBUTING.md) page first.

- [Integration Overview](#integration-overview)
- [Engine API](#engine-api)
- [On Demand App Generation](#on-demand-app-generation)
- [Mashup API](#mashup-api)
- [Visualization API](#visualization-api)
- [Capability APIs](#capability-apis)
- [Visualization Extensions](#visualization-extensions)
- [Qlik Sense Repository (QRS) API](#qlik-sense-repository-api)
- [Security](#security)
- [Connectivity](#connectivity)
- [.NET SDK](#net-sdk)

---

## Integration Overview

- [Qlik Analytics Platform / QAP](http://help.qlik.com/en-US/sense-developer/2.2/Subsystems/Platform/Content/Architecture/qlik-analytic-platform.htm) - Overview of the Qlik Analytics Platform

## Engine API

- [qsocks](https://github.com/mindspank/qsocks) - A lightweight promise wrapper around the Qlik Sense Engine API.
- [Engine API Explorer](http://qliksite.io/qlik-sense/introducing-engine-api-explorer/) - Introduction to the Engine API Explorer (a part of Dev Hub).
- [Engine API and qSocks](https://community.qlik.com/blogs/qlikviewdesignblog/2015/07/20/engine-api-and-qsocks-connecting-and-getting-a-list-of-available-apps) - Engine API and qSocks - Connecting and getting a list of available apps.
- [QlikSenseAngularDemo](https://github.com/thomasfriebel/QlikSenseAngularDemo) - A lightweight browser demo of the new Qlik Engine API.

## On Demand App generation
- [On demand app generation](https://github.com/websy85/on-demand-app-gen) - A simple On-demand app generation extension for Qlik Sense.
- [app-on-deman](https://github.com/bardess/app-on-demand) - On demand app generation
- [architeqt](https://github.com/mindspank/architeqt) - Generated Qlik Sense apps from a template
- [qlik-elastic](https://github.com/pouc/qlik-elastic) - Generated Qlik Sense apps from ElasticSearch

## Mashup API

- [Mashup API Tutorials](https://community.qlik.com/thread/140982) - Great series of tutorials how to get started with Mashups.
- [Extensions to the Mashup API](https://github.com/websy85/extended-mashup-api)
- [Qlik Analytics for Visual Studio](https://visualstudiogallery.msdn.microsoft.com/de8d2bfa-fd5e-44d5-ab23-f8bccdcc2ef0) - Visual Studio plugin to integrate Qlik Sense visualizations into an existing web site.

## Visualization API
- [The Visualization API - An Overview](http://branch.qlik.com/#/blog/56cc5f2af9e755b0dd301559)
- Some great gists, using the Visualization API:
    - [Basic Visualization API example.](https://jsfiddle.net/mindspank/803627ug/) - Connecting to Qlik Sense and displaying fully interactive graphs based on Qlik data.
    - [Patching properties on the fly](https://jsfiddle.net/mindspank/b6zob8ku/) -
    - [Selective Data points](https://jsfiddle.net/mindspank/1zqp7zuc/) -
    - [Visualization API and Extensions on the fly](https://jsfiddle.net/mindspank/rnmka3zh/) - Loading on the fly extensions and using the visualization api to display them.

## Capability APIs

- [WebPack-CapabilityAPIs](https://github.com/mindspank/webpack-capabilitiesapi) - Examples how to use the Capability APIs in combination with WebPack    

## Visualization Extensions

- [Qlik Sense Extension Tutorial](https://github.com/stefanwalther/qliksense-extension-tutorial) - Living tutorial on how to create visualization extensions, including sample code.
- [Qlik Sense Extension with D3](http://blog.axc.net/tutorial-how-to-build-a-qlik-sense-extension-with-d3/) - Tutorial: How to Build a Qlik Sense Extension with D3.
- [Using Bootstrap CSS in Qlik Sense Visualization Extensions](http://qliksite.io/qlik-sense/using-bootstrap-css-qliksense-visualization-extensions/) - How to prevent clashes between Qlik Sense' CSS files and those from Bootstrap.
- [Lasso filtering](http://blog.axc.net/lasso-filtering-in-qlik-sense-extensions/) - Lasso filtering in Qlik Sense Visualization Extensions.
- [Lasso plugin](https://github.com/skokenes/D3-Lasso-Plugin) - D3 plugin, very similar to the lasso in Qlik Sense.
- [Qlik-Sense-D3-Visualization-Library](https://github.com/skokenes/Qlik-Sense-D3-Visualization-Library) - A library of d3 visualizations housed in 1 Qlik Sense extension.
- [ES6, Babel, Webpack & GulpJS](https://github.com/alner/NewQlikSenseVisualizationTemplate) - Template for developing visualization extensions, using ES6, Babel, Webpack & GulpJS).

## Qlik Sense Repository API

- [Qlik-Cli](https://github.com/ahaydon/Qlik-Cli) - PowerShell Cmdlets to talk to the QRS API.
- [QlikSensePowerShell](https://github.com/JoeBickley/QlikSensePowerShell) - A powershell plugin with common Qlik Sense automation functions.

## Security

- [Authenticating with certificates](http://qliksite.io/qlik-sense/authentication-certificates/) - A step-by-step guide how to set up, configure and use certificates for authentication.
- [Using Header Authentication](http://qliksite.io/qlik-sense/header-authentication-configuration/) - A step-by-step guide how to set up and use header authentication.
- [qlik-auth](https://github.com/braathen/qlik-auth) - Node.js library to simplify custom authentication with both QlikView and Qlik Sense.
- [qlik-auth-net](https://github.com/braathen/qlik-auth-net) - Asp.net module for simplifying custom authentication with Qlik Sense.
- [qlik-auth-google](https://github.com/braathen/qlik-auth-google) - Qlik Sense OAuth2 authentication module designed specifically for Google services.
- [qlikoauth](https://github.com/braathen/qlikoauth) - Demonstration using OAuth 2.0 for QlikView and Qlik Sense integration.
- [Chrome Security Rule Management](https://github.com/flautrup/ChromeRuleManagement) - Chrome app developed to help the reuse and transfer of rules between Qlik Sense environments.
- [Using Capability APIs with tickets](https://github.com/mindspank/express-qps-sample) - Example how to use [Express](http://expressjs.com/) to host a page using the Capabilities API from Qlik Sense.

## Connectivity

- [Butler for Qlik Sense](https://github.com/mountaindude/qlik-sense-butler) - Connectivity proxy for Sense, features such as posting to Slack from load script, real-time forwarding of reload failures and user login/logout events to Slack and MQTT, and others.  
- []() -
- []() -

## .NET SDK

- [.NET SDK Examples](https://github.com/AptkQlik/PublicExamples) - Some examples using the .NET SDK.
- [Reloader NTLM](https://github.com/AptkQlik/Reloader_NTLM) - Example how to avoid consuming license tokens and how to use other credentials than the logged on user.
- [SDKConnectionWithSenseTicket](https://github.com/AptkQlik/SDKConnectionWithSenseTicket) - Connect with the Qlik Sense .Net SDK using an existing session.
- [ScriptReloader](https://github.com/AptkQlik/ScriptReloader) - Illustrate how one can decompose a Qlik Sense App so that scripts can be reloaded from an external server.
- [QlikSenseScriptObfuscater](https://github.com/AptkQlik/QlikSenseScriptObfuscater) - A way to hide scripts with .Net SDK in Qlik Sense.


# License

[![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

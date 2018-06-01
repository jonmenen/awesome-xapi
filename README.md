# Awesome xAPI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of developer resources for [**Webex Room and Desk Devices**](https://www.webex.com/products/devices/index.html) inspired by awesome-go and awesome-python.

> Looking for developer resources for **[Webex Teams](https://www.webex.com/products/teams/)**? check [awesome-webex](https://github.com/CiscoDevNet/awesome-webex).<br/>


### Contributing

Please take a quick gander at the [Contribution guidelines](./CONTRIBUTING.md) first. Thanks to all contributors; you rock!

If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!


### Contents

DISCLAIMER: Cisco does not make any commitments about the resources listed in this document, nor the accuracy of the third party resources and any content accessible via the links below.


- [Code samples](#code-samples)
- [Dev Tools](#developer-tools)
- [Reference](#reference)
   - [Online Documentation](#online-documentation)
   - [PDF Guides](#PDF-guides)
   - [Tutorials](#tutorials)


## Code samples

*Basic samples to end-to-end applications illustrating the xAPI capabilities.*

* In-Room Controls
   * [maze game](https://github.com/ObjectIsAdvantag/xapi-samples/tree/master/controls/maze) - Navigate blind in a maze, look for the treasure (by ObjectIsAdvantag).
* Node.js (jsxapi)
   * [jsxapi](https://github.com/cisco-ce/jsxapi) - JavaScript bindings for Cisco Collaboration Endpoint  XAPI (by Cisco CE).
   * [jsxapi samples](https://github.com/ObjectIsAdvantag/xapi-samples/tree/master/jsxapi) - Example scripts using the Node.js jsxapi (by ObjectIsAdvantag).
* Macros (Javascript)
   * [macros-sample](https://github.com/CiscoDevNet/roomdevices-macros-samples) - Selection of macros proposed by the xAPI dev team (by Cisco CE).
   * [xapi-samples](https://github.com/ObjectIsAdvantag/xapi-samples/tree/master/macros) - Macros to quickly ramp up with the xAPI of your Room Devices (by ObjectIsAdvantag).
* Misc demos
   * [MyRoomKit](https://github.com/CiscoDevNet/botkit-webex-samples/tree/master/roomkit) - Botkit chatbot as an extension of a RoomKit device (by ObjectIsAdvantag).  
   * [roomie](https://bitbucket.org/bjolseth/roomie) - App reporting whether there are people in the meeting rooms (by bjolseth).
   * [roomkit-react-map](https://github.com/ObjectIsAdvantag/roomkit-react-map) - React map showing PeopleCount analytics fired by a set of RoomKits (by ObjectIsAdvantag).
   * [telehealthPresence](https://github.com/voipnorm/telehealthPresence) - Add additional presence states for video endpoints in Jabber (by voipnorm).


## Developer Tools

*Handy tools to interact with CE devices.*

* [CiscoTPCustomXML](https://github.com/voipnorm/CiscoTPCustomXML) - Deploy packages to Cisco Telepresence apps (by voipnorm).
* DevNet Sandboxes - Reserve and code against a RoomKit device for up to a week 
   * [CE 9.2.1]() - RoomKit Sandbox equiped with CE 9.2.1.
   * [CE 9.3]() - RoomKit Sandbox equiped with CE 9.3.
* [Playground](https://controls-editor.herokuapp.com) - Experience the In-Room Controls Editor with no Webex device at hand (by ObjectIsAdvantag).
* [postman-xapi](https://github.com/CiscoDevNet/postman-xapi) - Postman collections for xAPI (by ObjectIsAdvantag).
* [roomkit-collector](https://github.com/ObjectIsAdvantag/roomkit-collector) - Collects PeopleCount from RoomKits and computes weighted averages (by ObjectIsAdvantag).
* [Send-XCommand](https://github.com/unifiedfx/Send-XCommand) - Powershell Cmdlets for sending xConfiguration & xCommand requests (by stephenwelsh).


## Reference

### Online Documentation

*Online documentation, product resources and technical support.*

* Reference Portals and Dev Centers
    * [Configuration guides](https://www.cisco.com/c/en/us/support/collaboration-endpoints/telepresence-quick-set-series/products-installation-and-configuration-guides-list.html) - Configure your Touch10 interface or 3rd party Video Switchers
    * [Developer Portal](https://developer.cisco.com/site/roomdevices/) - Technical resources for developers and integrators.
    * [Product resources](https://www.cisco.com/c/en/us/support/collaboration-endpoints/index.html) - Resources for all Supported Collaboration Endpoints.
    * [Project Workplace](https://projectworkplace.cisco.com) - Discover Cisco's devices portfolio, product features and recommandations.
* Online Help Articles
    * [Advanced Settings](https://collaborationhelp.cisco.com/article/en-us/n5pqqcm) - Advanced Settings for Room and Desk Devices
    * [Integrating](https://collaborationhelp.cisco.com/article/en-us/n18glho) - In-Room Controls and Use of an External Video Switch with Room Devices
    * [Local user](https://collaborationhelp.cisco.com/article/en-us/jkhs20) - Local User Administration on Room and Desk Devices
    * [Screens Setup Tips](https://collaborationhelp.cisco.com/article/en-us/nyi4lcq) - Recommended external screen settings for Room Devices.
* Technical Support
    * [Forums](https://supportforums.cisco.com/t5/telepresence/bd-p/5886-discussions-telepresence) - Telepresence forum by Cisco Support Community.
    * ['xAPI devs' space](https://eurl.io/#rkp76XDrG) - Chat live in Webex Teams with other developers.
* Troubleshooting
    * [CE Release notes](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/software/ce9/release-notes/ce-software-release-notes-ce9.pdf) - New features and functionality in CE9.
    * [Known issues](https://collaborationhelp.cisco.com/article/en-us/yurdv2) - Known and Resolved issues for Cloud-registered Room and Desk devices.
    * [What's new](https://collaborationhelp.cisco.com/article/en-us/DOC-10372) - New features and capabilities for Cloud-registered Room devices.
* 3rd-party Control Systems
    * [AMX/Harman](https://trade.amx.com/Net/Inconcert/Devices/inconcertmainpage.aspx)
    * [Creston](http://applicationmarket.crestron.com/cisco/)
    * [Extron](https://www.extron.com/company/article.aspx?id=ciscotouch)

### PDF Guides

*Administration guides, and API Reference for xConfiguration, xCommand, xStatus*

* CE 9.2
    * [Customization guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/sx-mx-dx-room-kit-customization-guide-ce92.pdf)
    * [DX70/DX80 - API Reference](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/dx70-dx80-api-reference-guide-ce92.pdf)
    * [RoomKit - Administration guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/room-kit-administrator-guide-ce92.pdf)
    * [RoomKit - API Reference](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/room-kit-api-reference-guide-ce92.pdf)
* CE 9.3
    * [Customization guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce93/sx-mx-dx-room-kit-customization-guide-ce93.pdf)

### Tutorials

* [Introduction](https://learninglabs.cisco.com/lab/collab-xapi-intro/step/1) - Learn to invoke your device's API via SSH, HTTP and Node.js (by Cisco DevNet).
* [In-Room Controls and Macros](https://learninglabs.cisco.com/lab/collab-xapi-controls/step/1) - Create an "Ultrasound Panel" and control it from Node.js and Macros (by Cisco DevNet).
* [Macro Scripting](https://github.com/ObjectIsAdvantag/xapi-samples/blob/master/macros/pdf/macro-tutorial.pdf) - Write your first Macro scripts (by Cisco CE).
* [Personalizing your device](https://learninglabs.cisco.com/lab/collab-xapi-branding/step/1) - Add your own logo and custom messages from code (by Cisco DevNet).
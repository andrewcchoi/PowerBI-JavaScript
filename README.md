# powerbi-client
A client side library for embedding Power BI using JavaScript or TypeScript into your apps.

[![Build Status](https://img.shields.io/travis/Microsoft/PowerBI-JavaScript/master.svg)](https://travis-ci.org/Microsoft/PowerBI-JavaScript)
[![NPM Version](https://img.shields.io/npm/v/powerbi-client.svg)](https://www.npmjs.com/package/powerbi-client)
[![Nuget Version](https://img.shields.io/nuget/v/Microsoft.PowerBI.JavaScript.svg)](https://www.nuget.org/packages/Microsoft.PowerBI.JavaScript/)
[![NPM Total Downloads](https://img.shields.io/npm/dt/powerbi-client.svg)](https://www.npmjs.com/package/powerbi-client)
[![NPM Monthly Downloads](https://img.shields.io/npm/dm/powerbi-client.svg)](https://www.npmjs.com/package/powerbi-client)
[![GitHub tag](https://img.shields.io/github/tag/microsoft/powerbi-javascript.svg)](https://github.com/Microsoft/PowerBI-JavaScript/tags)
[![Gitter](https://img.shields.io/gitter/room/Microsoft/PowerBI-JavaScript.svg)](https://gitter.im/Microsoft/PowerBI-JavaScript)

## Documentation
See the [Power BI embedded analytics Client APIs documentation](https://docs.microsoft.com/javascript/api/overview/powerbi/) to learn how to embed a Power BI report in your application and how to use the client APIs.

## Code Docs
See the [code docs](https://learn.microsoft.com/en-us/javascript/api/powerbi/powerbi-client) for detailed information about classes, interfaces, types, etc.

## Sample Application
For examples of applications utilizing the `powerbi-client` library, please refer to the  available samples in the [PowerBI-Developer-Samples repository](https://github.com/microsoft/PowerBI-Developer-Samples).

## Playground
To explore and understand the capabilities of embedded analytics in your applications, please visit the [Power BI Embedded Analytics Playground](https://playground.powerbi.com).

## Installation

Install via Nuget:

`Install-Package Microsoft.PowerBI.JavaScript`

Install from NPM:

`npm install --save powerbi-client`

Installing beta versions:

`npm install --save powerbi-client@beta`

## Include the library via import or manually

Ideally you would use a module loader or a compilation step to import using ES6 modules as:

```javascript
import * as pbi from 'powerbi-client';
```

However, the library is exported as a Universal Module and the powerbi.js script can be included before your app's closing `</body>` tag as:

```html
<script src="/powerbi-client/dist/powerbi.js"></script>
```

When included directly, the library is exposed as a global named `powerbi-client`.
There is also another global named `powerbi` which is an instance of the service.

## Contributing

This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit <https://cla.opensource.microsoft.com>.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments
#||# oslo-converter-ea for diagram OSLO-Toestemming

#||# -------------------------------------

2025-02-11T12:04:04.920Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T12:04:04.921Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:Domain Model) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T12:04:04.922Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:Domain Model:OSLO²_vocabularium) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T12:04:04.926Z warn: [ConnectorConverterHandler]: Connector (dataSubject) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T12:04:04.926Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (dataSubject) and the fallback URI (http://todo.com/) will be assigned.

2025-02-11T12:04:04.926Z warn: [ConnectorConverterHandler]: Connector (dataSubject) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T12:04:04.926Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (dataSubject) and the fallback URI (http://todo.com/) will be assigned.

2025-02-11T12:04:04.926Z warn: [ConnectorConverterHandler]: Connector (verwerker) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T12:04:04.926Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (verwerker) and the fallback URI (http://todo.com/) will be assigned.

2025-02-11T12:04:04.927Z warn: [ConnectorConverterHandler]: Connector (verwerkingsverantwoordelijke) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T12:04:04.927Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (verwerkingsverantwoordelijke) and the fallback URI (http://todo.com/) will be assigned.

2025-02-11T12:04:04.927Z warn: [ConnectorConverterHandler]: Connector (extraInformatie) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T12:04:04.927Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (extraInformatie) and the fallback URI (http://todo.com/) will be assigned.

Error: [AttributeConverterHandler]: Unable to find domain object for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-Mandaat:Lidmaatschap:lidVanTot).

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:46:23

    at Array.forEach (<anonymous>)

    at AttributeConverterHandler.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:43:26)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:31:50

    at Array.map (<anonymous>)

    at ConverterHandlerService.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:31:37)

#||# -------------------------------------

file toestemming.jsonld does not exist


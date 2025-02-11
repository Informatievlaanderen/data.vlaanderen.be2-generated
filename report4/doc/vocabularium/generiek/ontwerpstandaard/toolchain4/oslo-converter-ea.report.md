#||# oslo-converter-ea for diagram OSLO-Generiek

#||# -------------------------------------

2025-02-11T15:11:19.250Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T15:11:19.252Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:Domain Model) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T15:11:19.252Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:Domain Model:OSLO²_vocabularium) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T15:11:19.259Z warn: [ConnectorConverterHandler]: Connector (isLidVan) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T15:11:19.259Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (isLidVan) and the fallback URI (http://todo.com/) will be assigned.

2025-02-11T15:11:19.259Z warn: [ConnectorConverterHandler]: Connector (isLidVan) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T15:11:19.259Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (isLidVan) and the fallback URI (http://todo.com/) will be assigned.

2025-02-11T15:11:19.260Z warn: [ConnectorConverterHandler]: Connector (Lidmaatschap.Agent) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T15:11:19.260Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (Lidmaatschap.Agent) and the fallback URI (http://todo.com/) will be assigned.

2025-02-11T15:11:19.260Z warn: [ConnectorConverterHandler]: Connector (Lidmaatschap.Organisatie) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

Error: [AttributeConverterHandler]: Unable to find domain object for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-Mandaat:Lidmaatschap:lidVanTot).

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:46:23

    at Array.forEach (<anonymous>)

    at AttributeConverterHandler.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:43:26)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:31:50

    at Array.map (<anonymous>)

    at ConverterHandlerService.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:31:37)

#||# -------------------------------------

file generiek.jsonld does not exist


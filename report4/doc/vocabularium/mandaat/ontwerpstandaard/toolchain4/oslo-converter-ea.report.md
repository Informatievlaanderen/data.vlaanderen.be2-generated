#||# oslo-converter-ea for diagram OSLO-Mandaat

#||# -------------------------------------

2025-02-11T15:42:50.995Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T15:42:50.997Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:Domain Model) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T15:42:50.997Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:Domain Model:OSLO²_vocabularium) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T15:42:51.002Z warn: [ConnectorConverterHandler]: Connector (isTijdelijkVervangenDoor) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

Error: [AttributeConverterHandler]: Unable to find domain object for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-Mandaat:Lidmaatschap:lidVanTot).

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:46:23

    at Array.forEach (<anonymous>)

    at AttributeConverterHandler.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:43:26)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:31:50

    at Array.map (<anonymous>)

    at ConverterHandlerService.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:31:37)

#||# -------------------------------------

file mandaat.jsonld does not exist


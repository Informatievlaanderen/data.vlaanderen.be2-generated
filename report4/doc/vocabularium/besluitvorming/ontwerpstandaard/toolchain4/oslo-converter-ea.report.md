#||# oslo-converter-ea for diagram OSLO-Besluitvorming

#||# -------------------------------------

2025-02-11T10:11:41.737Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T10:11:41.739Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:OSLO²_vocabularium) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T10:11:41.744Z warn: [ConnectorConverterHandler]: Connector (beschrijft) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T10:11:41.744Z warn: [ConnectorConverterHandler]: Connector (beschrijft) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

Error: [AttributeConverterHandler]: Unable to find domain object for attribute (Model:OSLO²_vocabularium:OSLO-Notificatie:Notificatiekanaal:Passief).

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:46:23

    at Array.forEach (<anonymous>)

    at AttributeConverterHandler.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:43:26)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:31:50

    at Array.map (<anonymous>)

    at ConverterHandlerService.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:31:37)

#||# -------------------------------------

file besluitvorming.jsonld does not exist


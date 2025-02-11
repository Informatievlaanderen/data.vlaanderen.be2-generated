#||# oslo-converter-ea for diagram OSLO-Organisatie

#||# -------------------------------------

2025-02-11T16:11:26.144Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T16:11:26.146Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:Domain Model) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T16:11:26.146Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:Domain Model:OSLO²_vocabularium) and fallback URI (http://todo.com/) will be assigned.

2025-02-11T16:11:26.150Z warn: [ConnectorConverterHandler]: Connector (heeftVerwerkersovereenkomstMet) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T16:11:26.150Z warn: [ConnectorConverterHandler]: Connector (heeftVerwerkersovereenkomstMet) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T16:11:26.150Z warn: [ConnectorConverterHandler]: Connector (Verwerkersovereenkomst.PubliekeOrganisatie) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T16:11:26.151Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (Verwerkersovereenkomst.PubliekeOrganisatie) and the fallback URI (http://todo.com/) will be assigned.

2025-02-11T16:11:26.151Z warn: [ConnectorConverterHandler]: Connector (Verwerkersovereenkomst.Organisatie) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-02-11T16:11:26.151Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (Verwerkersovereenkomst.Organisatie) and the fallback URI (http://todo.com/) will be assigned.

Error: [AttributeConverterHandler]: Unable to find domain object for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-Notificatie:Notificatiekanaal:Passief).

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:46:23

    at Array.forEach (<anonymous>)

    at AttributeConverterHandler.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:43:26)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:31:50

    at Array.map (<anonymous>)

    at ConverterHandlerService.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:31:37)

#||# -------------------------------------

file organisatie.jsonld does not exist


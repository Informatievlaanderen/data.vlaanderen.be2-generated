#||# oslo-converter-ea for diagram OSLO-Mandaat

#||# -------------------------------------

2025-03-12T16:51:54.225Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Persoon:Persoon:heeftRelatieMet)

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Transactie:PubliekeDienstverlening (consumptie):isGerelateerdMet)

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Transactie:PubliekeDienstverlening (consumptie):vereist)

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Organisatie:Organisatie:isSuborganisatieVan)

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Organisatie:Organisatie:heeftSuborganisatie)

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Organisatie:Organisatie:isGeassocieerdMet)

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Mobiliteit:Verkeersbordbasis:(Verkeersbordbasis -> OSLO-OpenbaarDomein::Verkeersbord))

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Mobiliteit:Verkeersmaatregel:verwijstNaar)

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Organisatie:Organisatie:(Organisatie -> Object))

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Persoon:Persoon:(Persoon -> Object))

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:FormeelKader:(FormeelKader -> Object))

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:FormeelKader:isGerelateerdAan)

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Agent:isLidVan)

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Transactie:PubliekeDienstverlening (consumptie):wordtUitgevoerdDoor)

2025-03-12T16:51:54.227Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Agent:isLidVan)

2025-03-12T16:51:54.228Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Dienst:PubliekeDienstverlening:heeftVerantwoordelijke)

2025-03-12T16:51:54.228Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Dienst:PubliekeDienstverlening:vereist)

2025-03-12T16:51:54.228Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Dienst:PubliekeDienstverlening:isGerelateerdMet)

2025-03-12T16:51:54.228Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Wetgeving:Rechtsgrond:aangenomenDoor)

2025-03-12T16:51:54.228Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-Dienst:Kost:isGedefinieerdDoor)

2025-03-12T16:51:54.231Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model) and fallback URI (http://todo.com/) will be assigned.

2025-03-12T16:51:54.232Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:Domain Model) and fallback URI (http://todo.com/) will be assigned.

2025-03-12T16:51:54.232Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:Domain Model:OSLO²_vocabularium) and fallback URI (http://todo.com/) will be assigned.

2025-03-12T16:51:54.238Z warn: [ConnectorConverterHandler]: Connector (isTijdelijkVervangenDoor) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

Error: [AttributeConverterHandler]: Unable to find domain object for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-Mandaat:Lidmaatschap:lidVanTot).

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:51:23

    at Array.forEach (<anonymous>)

    at AttributeConverterHandler.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/AttributeConverterHandler.js:48:26)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:38:50

    at Array.map (<anonymous>)

    at ConverterHandlerService.assignUris (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:38:37)

#||# -------------------------------------

file mandaat.jsonld does not exist


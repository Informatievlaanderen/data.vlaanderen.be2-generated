#||# oslo-converter-ea for diagram OSLO-Netwerk-volledig

#||# -------------------------------------

#||# command: oslo-converter-ea --umlFile OSLO-Netwerk.EAP --diagramName OSLO-Netwerk-volledig --outputFile netwerk.jsonld --specificationType Vocabulary --versionId doc/vocabularium/netwerk/pieter --baseUri https://data.vlaanderen.be --debug true --publicationEnvironment https://data.dev-vlaanderen.be/

2026-10-08T12:44:45.789Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-Netwerk:Netwerkreferentie:(Netwerkreferentie -> Netwerkelement))

2026-10-08T12:44:45.792Z info: Connector Model:Domain Model:OSLO-Netwerk:Linkset:(Linkset -> Netwerkelement) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.793Z info: Connector Model:Domain Model:OSLO-Netwerk:GeneriekeLink:(GeneriekeLink -> Netwerkelement) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.793Z info: Connector Model:Domain Model:OSLO-Netwerk:Knoop:(Knoop -> Netwerkelement) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.793Z info: Connector Model:Domain Model:OSLO-Netwerk:Netwerkgebied:(Netwerkgebied -> Netwerkelement) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.793Z info: Connector Model:Domain Model:OSLO-Netwerk:Connectie:(Connectie -> Netwerkelement) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.793Z info: Connector Model:Domain Model:OSLO-Netwerk:Linksequentie:(Linksequentie -> GeneriekeLink) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.793Z info: Connector Model:Domain Model:OSLO-Netwerk:Link:(Link -> GeneriekeLink) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.793Z info: Connector Model:Domain Model:OSLO-Netwerk:Link:(Link -> Knoop) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.793Z info: Connector Model:Domain Model:OSLO-Netwerk:Link:(Link -> Knoop) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.793Z info: Connector Model:Domain Model:OSLO-Netwerk:Connectie:(Connectie -> Netwerkelement) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.793Z info: Connector Model:Domain Model:OSLO-Netwerk:Linkreferentie:(Linkreferentie -> Netwerkreferentie) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.793Z info: Connector Model:Domain Model:OSLO-Netwerk:LineaireReferentie:(LineaireReferentie -> Linkreferentie) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.794Z info: Connector Model:Domain Model:OSLO-Netwerk:Puntreferentie:(Puntreferentie -> Linkreferentie) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.794Z info: Connector Model:Domain Model:OSLO-Netwerk:GerichteLink:(GerichteLink -> Link) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.794Z info: Connector Model:Domain Model:OSLO-Netwerk:OngelijkgrondseKruising:(OngelijkgrondseKruising -> Netwerkelement) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.794Z info: Connector Model:Domain Model:OSLO-Netwerk:OngelijkgrondseKruising:(OngelijkgrondseKruising -> Link) is not an association with a source role. Ignoring this connector.

2026-10-08T12:44:45.794Z info: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model). Using fallback URI (http://todo.com/) instead.

2026-10-08T12:44:45.795Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Domain Model). Using fallback URI (http://todo.com/) instead.

2026-10-08T12:44:45.796Z warn: [ConnectorConverterHandler]: Connector (inNetwerk) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-10-08T12:44:45.797Z warn: [ConnectorConverterHandler]: Connector (bestaatUit) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-10-08T12:44:45.797Z warn: [ConnectorConverterHandler]: Connector (beginknoop) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-10-08T12:44:45.797Z warn: [ConnectorConverterHandler]: Connector (eindknoop) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-10-08T12:44:45.797Z warn: [ConnectorConverterHandler]: Connector (link) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-10-08T12:44:45.797Z warn: [ConnectorConverterHandler]: Connector (kruisingVan) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-10-08T12:44:45.797Z warn: [ConnectorConverterHandler]: Connector (link) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-10-08T12:44:45.797Z warn: [ConnectorConverterHandler]: Connector (verbindt) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-10-08T12:44:45.801Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO-Netwerk:Puntreferentie:opPositie).

2026-10-08T12:44:45.801Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO-Netwerk:LineaireReferentie:vanPositie).

2026-10-08T12:44:45.801Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO-Netwerk:LineaireReferentie:totPositie).

2026-10-08T12:44:45.801Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO-Netwerk:Linkreferentie:element).

2026-10-08T12:44:45.802Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO-Netwerk:GerichteLink:richting).

#||# -------------------------------------

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/vocabularium/netwerk/pieter/all-netwerk.jsonld -o /tmp/reportlines  


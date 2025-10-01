#||# oslo-converter-ea for diagram OSLO-Grondboringen-Bemonstering

#||# -------------------------------------

2025-10-01T20:23:25.159Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-Grondboringen:Boorgat:(Boorgat -> Grondmonster))

2025-10-01T20:23:25.161Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-Generiek:Agent:rapporteertAan)

2025-10-01T20:23:25.162Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-BO_Observaties:Schuifweerstandproef:(Schuifweerstandproef -> Schuifweerstandproef))

2025-10-01T20:23:25.162Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-BO_Observaties:Schuifweerstandskarakteristieken:(Schuifweerstandskarakteristieken -> Schuifweerstandproef))

2025-10-01T20:23:25.162Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-ObservatiesEnMetingen:Monster:(Monster -> BemonsteringsProces))

2025-10-01T20:23:25.162Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:SSN/SOSA:Bemonstering:(Bemonstering -> Grondobject))

2025-10-01T20:23:25.162Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-ObservatiesEnMetingen:Bemonsteringsobject:(Bemonsteringsobject -> Grondobject))

2025-10-01T20:23:25.166Z info: Connector Model:Domain Model:Hulppakket:Bemonsteringsobject:(Bemonsteringsobject -> Object) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.167Z info: Connector Model:Domain Model:OSLO-ObservatiesEnMetingen:Bemonsteringsobject:(Bemonsteringsobject -> Bemonsteringsobject) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.168Z info: Connector Model:Domain Model:Hulppakket:Bemonsteringsobject:(Bemonsteringsobject -> Object) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.168Z info: Connector Model:Domain Model:OSLO-Grondboringen:Grondmonster:(Grondmonster -> Bemonsteringsobject) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.168Z info: Connector Model:Domain Model:OSLO-Grondboringen:Grondboring:(Grondboring -> Bemonstering) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.168Z info: Connector Model:Domain Model:OSLO-Besluit:LegaleVerschijningsvorm:(LegaleVerschijningsvorm -> Rechtsgrond) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.169Z info: Connector Model:Domain Model:OSLO-Generiek:Curve:(Curve -> Geometrie) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.169Z info: Connector Model:Domain Model:OSLO-ObservatiesEnMetingen:Domeinobject:(Domeinobject -> Object) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.169Z info: Connector Model:Domain Model:SSN/SOSA:Bemonstering:(Bemonstering -> Bemonsteringsprocedure) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.169Z info: Connector Model:Domain Model:OSLO-Grondboringen:Boorgat:(Boorgat -> Bemonsteringsobject) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.169Z info: Connector Model:Domain Model:SSN/SOSA:Bemonstering:(Bemonstering -> Object) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.170Z info: Connector Model:Domain Model:OSLO-Grondboringen:Boormethode:(Boormethode -> Bemonsteringsprocedure) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.170Z info: Connector Model:Domain Model:OSLO-Grondboringen:Boor:(Boor -> Bemonsteraar) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.170Z info: Connector Model:Domain Model:OSLO-Grondboringen:WettelijkKaderBoring:(WettelijkKaderBoring -> WettelijkKader) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.170Z info: Connector Model:Domain Model:OSLO-Grondboringen:Grondobject:(Grondobject -> Domeinobject) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.170Z info: Connector Model:Domain Model:OSLO-ObservatiesEnMetingen:Bemonsteringsobject:(Bemonsteringsobject -> Object) is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.170Z info: Connector Model:Domain Model:OSLO-ObservatiesEnMetingen:Bemonsteringsobject:Intentie is not an association with a source role. Ignoring this connector.

2025-10-01T20:23:25.170Z info: Connector Model:Domain Model:OSLO-ObservatiesEnMetingen:Bemonsteringsobject:Intentie has name "Intentie". but no destination role. Ignoring therefore this connector. If required to be present add a role or cardinality.

Error: Unable to find the association class object for connector with path Model:Domain Model:OSLO-ObservatiesEnMetingen:Bemonsteringsobject:(Bemonsteringsobject -> Bemonsteringsobject).

    at SelfAssociationWithAssociationClassConnectorCase.normalise (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/connector-normalisation-cases/SelfAssociationWithAssociationClassConnectorCase.js:52:19)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConnectorNormalisationService.js:21:54

    at Array.map (<anonymous>)

    at ConnectorNormalisationService.normalise (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConnectorNormalisationService.js:21:41)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/ConnectorConverterHandler.js:48:68

    at Array.map (<anonymous>)

    at ConnectorConverterHandler.normalize (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/ConnectorConverterHandler.js:48:14)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:27:39

    at Array.map (<anonymous>)

    at ConverterHandlerService.normalize (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:27:14)

#||# -------------------------------------

file grondboringen.jsonld does not exist


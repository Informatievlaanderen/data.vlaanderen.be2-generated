#||# oslo-converter-ea for diagram OSLO-Grondboringen-Bemonstering

#||# -------------------------------------

2025-03-17T14:27:48.456Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-Grondboringen:Boorgat:(Boorgat -> Grondmonster))

2025-03-17T14:27:48.458Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-Generiek:Agent:rapporteertAan)

2025-03-17T14:27:48.458Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-BO_Observaties:Schuifweerstandproef:(Schuifweerstandproef -> Schuifweerstandproef))

2025-03-17T14:27:48.458Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-BO_Observaties:Schuifweerstandskarakteristieken:(Schuifweerstandskarakteristieken -> Schuifweerstandproef))

2025-03-17T14:27:48.458Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-ObservatiesEnMetingen:Monster:(Monster -> BemonsteringsProces))

2025-03-17T14:27:48.458Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:SSN/SOSA:Bemonstering:(Bemonstering -> Grondobject))

2025-03-17T14:27:48.458Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-ObservatiesEnMetingen:Bemonsteringsobject:(Bemonsteringsobject -> Grondobject))

2025-03-17T14:27:48.463Z info: Connector Model:Domain Model:Hulppakket:Bemonsteringsobject:Intentie is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.464Z info: Connector Model:Domain Model:OSLO-ObservatiesEnMetingen:Bemonsteringsobject:(Bemonsteringsobject -> Bemonsteringsobject) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.464Z info: Connector Model:Domain Model:Hulppakket:Bemonsteringsobject:(Bemonsteringsobject -> Object) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.464Z info: Connector Model:Domain Model:OSLO-Grondboringen:Grondmonster:(Grondmonster -> Bemonsteringsobject) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.464Z info: Connector Model:Domain Model:OSLO-Grondboringen:Grondboring:(Grondboring -> Bemonstering) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.465Z info: Connector Model:Domain Model:OSLO-Besluit:LegaleVerschijningsvorm:(LegaleVerschijningsvorm -> Rechtsgrond) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.465Z info: Connector Model:Domain Model:OSLO-Generiek:Curve:(Curve -> Geometrie) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.465Z info: Connector Model:Domain Model:OSLO-Grondboringen:Boorgatdiameter:(Boorgatdiameter -> Boorgat) has no name. Ignoring this connector.

2025-03-17T14:27:48.465Z info: Connector Model:Domain Model:OSLO-Grondboringen:Bekisting:(Bekisting -> Boorgat) has no name. Ignoring this connector.

2025-03-17T14:27:48.465Z info: Connector Model:Domain Model:OSLO-ObservatiesEnMetingen:Domeinobject:(Domeinobject -> Object) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.465Z info: Connector Model:Domain Model:SSN/SOSA:Bemonstering:(Bemonstering -> Bemonsteringsprocedure) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.465Z info: Connector Model:Domain Model:SSN/SOSA:Bemonstering:(Bemonstering -> Bemonsteraar) has no name. Ignoring this connector.

2025-03-17T14:27:48.465Z info: Connector Model:Domain Model:OSLO-Grondboringen:Boorgat:(Boorgat -> Bemonsteringsobject) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.465Z info: Connector Model:Domain Model:SSN/SOSA:Bemonsteraar:(Bemonsteraar -> Bemonsteringsprocedure) has no name. Ignoring this connector.

2025-03-17T14:27:48.466Z info: Connector Model:Domain Model:SSN/SOSA:Bemonstering:(Bemonstering -> Bemonsteringsobject) has no name. Ignoring this connector.

2025-03-17T14:27:48.466Z info: Connector Model:Domain Model:SSN/SOSA:Bemonstering:(Bemonstering -> Object) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.466Z info: Connector Model:Domain Model:OSLO-Grondboringen:Boorgat:(Boorgat -> Grondboring) has no name. Ignoring this connector.

2025-03-17T14:27:48.466Z info: Connector Model:Domain Model:OSLO-Grondboringen:Boormethode:(Boormethode -> Bemonsteringsprocedure) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.466Z info: Connector Model:Domain Model:OSLO-Grondboringen:Boor:(Boor -> Bemonsteraar) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.466Z info: Connector Model:Domain Model:OSLO-Grondboringen:WettelijkKaderBoring:(WettelijkKaderBoring -> WettelijkKader) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.466Z info: Connector Model:Domain Model:OSLO-Grondboringen:Grondobject:(Grondobject -> Domeinobject) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.466Z info: Connector Model:Domain Model:OSLO-ObservatiesEnMetingen:Bemonsteringsobject:(Bemonsteringsobject -> Object) is not an association with a source role. Ignoring this connector.

2025-03-17T14:27:48.466Z info: Connector Model:Domain Model:OSLO-ObservatiesEnMetingen:Bemonsteringsobject:Intentie is not an association with a source role. Ignoring this connector.

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


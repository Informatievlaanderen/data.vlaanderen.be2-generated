#||# oslo-converter-ea for diagram OSLO-BodemEnOndergrond

#||# -------------------------------------

2025-05-14T12:31:33.106Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-Grondboringen:Boorgat:(Boorgat -> Grondmonster))

2025-05-14T12:31:33.107Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-Generiek:Agent:rapporteertAan)

2025-05-14T12:31:33.107Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-BO_Observaties:Schuifweerstandproef:(Schuifweerstandproef -> Schuifweerstandproef))

2025-05-14T12:31:33.107Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-BO_Observaties:Schuifweerstandskarakteristieken:(Schuifweerstandskarakteristieken -> Schuifweerstandproef))

2025-05-14T12:31:33.107Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-ObservatiesEnMetingen:Monster:(Monster -> BemonsteringsProces))

2025-05-14T12:31:33.107Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:SSN/SOSA:Bemonstering:(Bemonstering -> Grondobject))

2025-05-14T12:31:33.108Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO-ObservatiesEnMetingen:Bemonsteringsobject:(Bemonsteringsobject -> Grondobject))

2025-05-14T12:31:33.112Z info: Connector Model:Domain Model:OSLO-ObservatiesEnMetingen:RuimtelijkBemonsteringsobject:(RuimtelijkBemonsteringsobject -> Bemonsteringsobject) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.112Z info: Connector Model:Domain Model:OSLO-ObservatiesEnMetingen:Bemonsteringsobject:(Bemonsteringsobject -> Bemonsteringsobject) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.113Z info: Connector Model:Domain Model:OSLO-Grondboringen:Grondboring:(Grondboring -> Bemonstering) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.113Z info: Connector Model:Domain Model:OSLO-Generiek:Punt:(Punt -> Geometrie) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.113Z info: Connector Model:Domain Model:OSLO-Generiek:Curve:(Curve -> Geometrie) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.113Z info: Connector Model:Domain Model:OSLO-Generiek:Vlak:(Vlak -> Geometrie) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.113Z info: Connector Model:Domain Model:OSLO-BodemEnOndergrond:Fractiemeting:(Fractiemeting -> Meetreeks) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.114Z info: Connector Model:Domain Model:OSLO-Generiek:3Dobject:(3Dobject -> Geometrie) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.114Z info: Connector Model:Domain Model:OSLO-ObservatiesEnMetingen:Profiel:(Profiel -> RuimtelijkBemonsteringsobject) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.114Z info: Connector Model:Domain Model:OSLO-BodemEnOndergrond:BO_RuimtelijkBemonsteringsobject:(BO_RuimtelijkBemonsteringsobject -> RuimtelijkBemonsteringsobject) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.114Z info: Connector Model:Domain Model:OSLO-BodemEnOndergrond:Laag:(Laag -> Interval) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.114Z info: Connector Model:Domain Model:OSLO-BodemEnOndergrond:Profielelement:(Profielelement -> RuimtelijkBemonsteringsobject) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.114Z info: Connector Model:Domain Model:OSLO-BodemEnOndergrond:Fractiemetingwaarde:(Fractiemetingwaarde -> Meetreekswaarde) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.114Z info: Connector Model:Domain Model:OSLO-BodemEnOndergrond:Fractiemetingresultaat:(Fractiemetingresultaat -> Meetreeksresultaat) is not an association with a source role. Ignoring this connector.

2025-05-14T12:31:33.114Z info: Connector Model:Domain Model:Hulppakket:Interval:(Interval -> Profielelement) is not an association with a source role. Ignoring this connector.

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

file bodem-en-ondergrond.jsonld does not exist


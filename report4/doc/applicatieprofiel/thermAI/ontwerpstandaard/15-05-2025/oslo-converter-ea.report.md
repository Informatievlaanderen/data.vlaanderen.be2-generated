#||# oslo-converter-ea for diagram ThermAI

#||# -------------------------------------

2025-05-14T09:48:52.485Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:SSN/SOSA:ObserveerbaarKenmerk:(ObserveerbaarKenmerk -> Sensor))

2025-05-14T09:48:52.487Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model-Energiehuis:OSLO-Generiek:Gemeente:(Gemeente -> Object))

2025-05-14T09:48:52.487Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model-Energiehuis:OSLO-Generiek:FormeelKader:(FormeelKader -> Object))

2025-05-14T09:48:52.487Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model-Energiehuis:OSLO-Energiehuis:Plaatsbezoek:(Plaatsbezoek -> Basistaak))

2025-05-14T09:48:52.487Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model-Energiehuis:OSLO-Persoon:Persoon:(Persoon -> Persoon))

2025-05-14T09:48:52.487Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model:ML-DCAT:MachineLearning Model:(MachineLearning Model -> MachineLearning Model))

2025-05-14T09:48:52.487Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model:ML-DCAT:MachineLearning Model:(MachineLearning Model -> MachineLearning Model))

2025-05-14T09:48:52.487Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model:DCAT:Dataset:(Dataset -> Dataset))

2025-05-14T09:48:52.487Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model:DCAT:Dataset:(Dataset -> Dataset))

2025-05-14T09:48:52.490Z info: Connector Model:SSN/SOSA:Observatie:(Observatie -> Observatie) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.491Z info: Connector Model:SSN/SOSA:Observatie:(Observatie -> ObserveerbaarKenmerk) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.491Z info: Connector Model:SSN/SOSA:Observatie:(Observatie -> Observatieprocedure) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.492Z info: Connector Model:Model:GPS:(GPS -> Sensor) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.492Z info: Connector Model:Model:Camera:(Camera -> Sensor) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.492Z info: Connector Model:Model:SSN/SOSA2:Platform:(Platform -> Platform) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.492Z info: Connector Model:Model:SAREF:Toestel:(Toestel -> Systeem) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.493Z info: Connector Model:Model:Opstelling:(Opstelling -> Sensor) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.493Z info: Connector Model:OSLO-Gebouw:Gebouw:(Gebouw -> Gebouweenheid) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.493Z info: Connector Model:OSLO-Gebouw:Gebouw:(Gebouw -> Domeinobject) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.493Z info: Connector Model:OSLO-Gebouw:Gebouweenheid:(Gebouweenheid -> Domeinobject) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.493Z info: Connector Model:Model:Video:(Video -> Domeinobject) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.493Z info: Connector Model:Model:Interpretatie:(Interpretatie -> Observatie) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.493Z info: Connector Model:SSN/SOSA:Observatieverzameling:(Observatieverzameling -> Observatieverzameling) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.494Z info: Connector Model:Model:OM:Meting:(Meting -> Observatie) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.494Z info: Connector Model:Model:OM:Classificatie:(Classificatie -> Observatie) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.494Z info: Connector Model:Model:OM:GeometrieObservatie:(GeometrieObservatie -> Observatie) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.494Z info: Connector Model:Model:Foto:(Foto -> Domeinobject) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.494Z info: Connector Model:Model:IFC:BIM_Element:(BIM_Element -> BIM_Gebouw) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.494Z info: Connector Model:Model:IFC:BIM_Gebouw:(BIM_Gebouw -> Domeinobject) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.494Z info: Connector Model:Model:IFC:BIM_Element:(BIM_Element -> Domeinobject) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.494Z info: Connector Model:Model:ML-DCAT:MachineLearning Model:(MachineLearning Model -> Sensor) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.494Z info: Connector Model:Model:OMS:Domeinobject:(Domeinobject -> Any) is not an association with a source role. Ignoring this connector.

2025-05-14T09:48:52.494Z info: Connector Model:Model:RDFS:Any:(Any -> Any) is not an association with a source role. Ignoring this connector.

Error: Unable to find the association class object for connector with path Model:SSN/SOSA:Observatie:(Observatie -> Observatie).

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

file ThermAI.jsonld does not exist


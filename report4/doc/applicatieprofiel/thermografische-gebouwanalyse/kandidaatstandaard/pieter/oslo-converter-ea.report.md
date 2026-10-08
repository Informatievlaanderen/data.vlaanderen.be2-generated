#||# oslo-converter-ea for diagram ThermAI

#||# -------------------------------------

#||# command: oslo-converter-ea --umlFile ThermAI.eap --diagramName ThermAI --outputFile thermografische-gebouwanalyse.jsonld --specificationType ApplicationProfile --versionId doc/applicatieprofiel/thermografische-gebouwanalyse/kandidaatstandaard/pieter --baseUri https://data.vlaanderen.be --debug true --publicationEnvironment https://data.dev-vlaanderen.be/

2026-10-08T19:27:52.256Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:SSN/SOSA:ObserveerbaarKenmerk:(ObserveerbaarKenmerk -> Sensor))

2026-10-08T19:27:52.257Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Energiehuis:Plaatsbezoek:(Plaatsbezoek -> Basistaak))

2026-10-08T19:27:52.257Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model:ML-DCAT:MachineLearningModel:(MachineLearningModel -> MachineLearningModel))

2026-10-08T19:27:52.257Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model:ML-DCAT:MachineLearningModel:(MachineLearningModel -> MachineLearningModel))

2026-10-08T19:27:52.257Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model:DCAT:Dataset:(Dataset -> Dataset))

2026-10-08T19:27:52.257Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model:DCAT:Dataset:(Dataset -> Dataset))

2026-10-08T19:27:52.257Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:SSN/SOSA:Any:(Any -> Any))

2026-10-08T19:27:52.257Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Model:OSLO-ObservatiesEnMetingen:Monster:(Monster -> BemonsteringsProces))

2026-10-08T19:27:52.260Z info: Connector Model:OSLO-Gebouw:Gebouw:(Gebouw -> Object) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.260Z info: Connector Model:Model:Schema.org:Video:(Video -> Object) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.260Z info: Connector Model:Model:QUDT:Eenheid:(Eenheid -> Concept) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.260Z info: Connector Model:SSN/SOSA:Sensor:(Sensor -> Systeem) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.260Z info: Connector Model:Model:ML-DCAT:MachineLearningModel:(MachineLearningModel -> Systeem) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.260Z info: Connector Model:SSN/SOSA:Observatie:(Observatie -> ObserveerbaarKenmerk) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.261Z info: Connector Model:SSN/SOSA:Observatie:(Observatie -> Observatieprocedure) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.261Z info: Connector Model:Model:ThermAI:GNSS Ontvanger:(GNSS Ontvanger -> Sensor) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.261Z info: Connector Model:Model:ThermAI:Camera:(Camera -> Sensor) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.261Z info: Connector Model:W3C-Time:Periode:(Periode -> TemporeleEntiteit) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.261Z info: Connector Model:W3C-Time:Moment:(Moment -> TemporeleEntiteit) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:Model:SAREF:Toestel:(Toestel -> Systeem) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:Model:ThermAI:Opstelling:(Opstelling -> Sensor) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:OSLO-Gebouw:Gebouw:(Gebouw -> Gebouweenheid) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:OSLO-Adres:Adresvoorstelling:(Adresvoorstelling -> Adres) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:OSLO-Gebouw:Gebouweenheid:(Gebouweenheid -> Object) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:SSN/SOSA:Observatieverzameling:(Observatieverzameling -> Observatieverzameling) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:Model:Schema.org:Video:(Video -> Informatieobject) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:Model:Schema.org:Foto:(Foto -> Object) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:Model:IFC:BIM_Element:(BIM_Element -> BIM_Gebouw) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:Model:IFC:BIM_Gebouw:(BIM_Gebouw -> Object) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:Model:IFC:BIM_Element:(BIM_Element -> Object) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:Model:Schema.org:Foto:(Foto -> Informatieobject) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.262Z info: Connector Model:Model:ML-DCAT:MachineLearningModel:(MachineLearningModel -> Sensor) is not an association with a source role. Ignoring this connector.

2026-10-08T19:27:52.263Z info: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model). Using fallback URI (http://todo.com/) instead.

#||# -------------------------------------

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/thermografische-gebouwanalyse/kandidaatstandaard/pieter/all-thermografische-gebouwanalyse.jsonld -o /tmp/reportlines  


#||# oslo-converter-ea for diagram Wegenvignetregistratie

#||# -------------------------------------

#||# command: oslo-converter-ea --umlFile OSLO-wegenvignetregistratie-IM.eap --diagramName Wegenvignetregistratie --outputFile wegenvignetregistratie.jsonld --specificationType ApplicationProfile --versionId doc/implementatiemodel/magda/wegenvignetregistratie/v0.1.0 --baseUri https://data.vlaanderen.be --debug true --publicationEnvironment https://data.dev-vlaanderen.be/

2026-10-15T09:00:37.574Z info: Connector Model:Wegenvignetregistratie:OSLO-Voertuigregistratie:Registratie:(Registratie -> Nummerplaat) is not an association with a source role. Ignoring this connector.

2026-10-15T09:00:37.576Z info: Connector Model:Wegenvignetregistratie:Schema.org:Voertuig:(Voertuig -> MotorSpecificatie) is not an association with a source role. Ignoring this connector.

2026-10-15T09:00:37.576Z info: Connector Model:Wegenvignetregistratie:OSLO-Wegenvignetregistratie:Wegenvignetregistratie:(Wegenvignetregistratie -> Registratie) is not an association with a source role. Ignoring this connector.

2026-10-15T09:00:37.576Z info: Connector Model:Wegenvignetregistratie:OSLO-Voertuigregistratie:Registratie:(Registratie -> Voertuig) is not an association with a source role. Ignoring this connector.

2026-10-15T09:00:37.577Z info: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model). Using fallback URI (http://todo.com/) instead.

#||# -------------------------------------

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/implementatiemodel/magda/wegenvignetregistratie/v0.1.0/all-wegenvignetregistratie.jsonld -o /tmp/reportlines  


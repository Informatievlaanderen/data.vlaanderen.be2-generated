#||# oslo-converter-ea for diagram Klantvolgsysteem

#||# -------------------------------------

2025-10-27T17:59:55.235Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:W3C-Person:Persoon:(Persoon -> Persoon))

2025-10-27T17:59:55.237Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:W3C-Person:Persoon:(Persoon -> Jurisdictie))

2025-10-27T17:59:55.237Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:W3C-ORG:Organisatie:(Organisatie -> Agent))

2025-10-27T17:59:55.237Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Dossier:Stuk:(Stuk -> Stuk))

2025-10-27T17:59:55.237Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Dossier:Activiteit:vindtPlaatsTijdens)

2025-10-27T17:59:55.237Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Dossier:Stukonderdeel:(Stukonderdeel -> Representatie))

2025-10-27T17:59:55.237Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:OSLO-Dossier:Activiteit:(Activiteit -> EenheidVanWerk))

2025-10-27T17:59:55.239Z info: Connector Model:OSLO-Persoon:Inwonerschap:(Inwonerschap -> Verblijfplaats) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.240Z info: Connector Model:OSLO-Persoon:Domicilie:(Domicilie -> Verblijfplaats) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.240Z info: Connector Model:OSLO-Persoon:GeregistreerdPersoon:(GeregistreerdPersoon -> Persoon) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.240Z info: Connector Model:Klantvolgsysteem:Deeltraject:(Deeltraject -> Output) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.240Z info: Connector Model:EU-CPSV:PubliekeDienstverlening:(PubliekeDienstverlening -> Input) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.241Z info: Connector Model:Klantvolgsysteem:Activeringstraject:(Activeringstraject -> Traject) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.241Z info: Connector Model:Klantvolgsysteem:Werknemerprofiel:(Werknemerprofiel -> Input) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.241Z info: Connector Model:Klantvolgsysteem:Inburgeringstraject:(Inburgeringstraject -> Traject) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.241Z info: Connector Model:W3C-Person:Persoon:(Persoon -> Werknemerprofiel) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.241Z info: Connector Model:EU-M8G:PubliekeOrganisatie:(PubliekeOrganisatie -> Organisatie) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.241Z info: Connector Model:W3C-ORG:Organisatie:(Organisatie -> Organisatie) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.241Z info: Connector Model:W3C-ORG:Organisatie:(Organisatie -> Organisatie) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.241Z info: Connector Model:W3C-ORG:Organisatie:(Organisatie -> Organisatie) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.242Z info: Connector Model:W3C-ORG:Organisatie:(Organisatie -> Agent) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.242Z info: Connector Model:OSLO-Persoon:Gezin:(Gezin -> Organisatie) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.242Z info: Connector Model:FOAF:Agent:(Agent -> PubliekeDienstverlening) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.242Z info: Connector Model:W3C-Person:Persoon:(Persoon -> Agent) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.242Z info: Connector Model:W3C-REGORG:GeregistreerdeOrganisatie:(GeregistreerdeOrganisatie -> Organisatie) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.242Z info: Connector Model:EU-CPSV:PubliekeDienstverlening:(PubliekeDienstverlening -> Output) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.242Z info: Connector Model:Klantvolgsysteem:Traject:(Traject -> Output) is not an association with a source role. Ignoring this connector.

2025-10-27T17:59:55.243Z info: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model). Using fallback URI (http://todo.com/) instead.

2025-10-27T17:59:55.243Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:W3C-Person). Using fallback URI (http://todo.com/) instead.

2025-10-27T17:59:55.243Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:W3C-REGORG). Using fallback URI (http://todo.com/) instead.

2025-10-27T17:59:55.247Z warn: [ConnectorConverterHandler]: Connector (deel) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-10-27T17:59:55.247Z warn: [ConnectorConverterHandler]: Connector (profiel) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-10-27T17:59:55.247Z warn: [ConnectorConverterHandler]: Can not determine the correct base URI for connector (profiel) and the fallback URI (http://todo.com/) will be assigned.

2025-10-27T17:59:55.249Z info: [ElementConverterHandler]: Ignoring SKOS Concept element (Model:EU-OP-AUTH:Taalcode) with URI http://www.w3.org/2004/02/skos/core#Concept

2025-10-27T17:59:55.271Z warn: [ConverterHandler]: Entity with path gezinslid has already a value for ap-definition-nl in language nl, but will be overwritten.

#||# -------------------------------------


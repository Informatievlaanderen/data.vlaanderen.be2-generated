#||# oslo-converter-ea for diagram OSLO-geodcatap

#||# -------------------------------------

2026-06-23T14:40:35.468Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusResource:(CatalogusResource -> Agent))

2026-06-23T14:40:35.469Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusResource:(CatalogusResource -> Agent))

2026-06-23T14:40:35.469Z info: [ConnectorConverterHandler]: Ignoring hidden connector (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusResource:(CatalogusResource -> CatalogusResource))

2026-06-23T14:40:35.471Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord:(CatalogusRecord -> CatalogusResource) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.472Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:(Catalogus -> CatalogusRecord) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.472Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusResource:(CatalogusResource -> Agent) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.472Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:(DataService -> Dataset) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.472Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:(DataService -> CatalogusResource) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.473Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:(Dataset -> CatalogusResource) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.473Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:(Distributie -> DataService) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.473Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:(Catalogus -> Agent) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.473Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:(Catalogus -> Dataset) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.473Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:(Dataset -> Distributie) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.473Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:(Catalogus -> DataService) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.474Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:(Dataset -> Agent) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.474Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:(Distributie -> Agent) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.474Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:(Dataset -> DatasetSerie) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.474Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusResource:(CatalogusResource -> CatalogusResource) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.474Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:(DatasetSerie -> Agent) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.474Z info: Connector Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Contactinfo:(Contactinfo -> ContactInfo) is not an association with a source role. Ignoring this connector.

2026-06-23T14:40:35.475Z info: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model). Using fallback URI (http://todo.com/) instead.

2026-06-23T14:40:35.475Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Domain Model). Using fallback URI (http://todo.com/) instead.

2026-06-23T14:40:35.475Z warn: [PackageConverterHandler]: No value found for tag "baseURI" in package (Model:Domain Model:OSLO²_vocabularium). Using fallback URI (http://todo.com/) instead.

2026-06-23T14:40:35.477Z warn: [ConnectorConverterHandler]: Connector (CatalogusResource (source)) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-06-23T14:40:35.477Z warn: [ConnectorConverterHandler]: Connector (CatalogusResource (target)) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2026-06-23T14:40:35.479Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus): DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.480Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord): DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.480Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusResource): DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.480Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset): DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.480Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.481Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie): DCAT, DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.481Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.481Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService): DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.481Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.481Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:JuridischeBepaling): reuse, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.481Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Plaats): DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.481Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:HerkomstVerklaring): reuse. These tags will be added.

2026-06-23T14:40:35.481Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:VoorbeeldWeergave): DCAT. These tags will be added.

2026-06-23T14:40:35.482Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:TemporalLiteral): class-usage-scope, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.482Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:TimeInstant): class-usage-scope, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.482Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie): property-usage-scope, class-usage-scope, DCAT, DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.482Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.482Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:ContactInfo): GEODCATAP. These tags will be added.

2026-06-23T14:40:35.482Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Contactinfo): DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.483Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Standaard): DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.483Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:LicentieDocument): DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.483Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Agent): DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.483Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Identificator): DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.483Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Resolutie): reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.483Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:RelatieQualificatie): DCAT, DCATAP, target-label-nl, target-definition-nl, source-definition-nl, source-label-nl, uri-source-attribute, uri-target-attribute, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.483Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:RelatieQualificatie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.484Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:dct:PeriodOfTime): class-usage-scope, DCAT, DCATAP, reuse, property-usage-scope, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.484Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:dct:PeriodOfTime has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.484Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Rechtsgrond): class-usage-scope, DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.484Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:alternatieveIdentificator): property-usage-scope, reuse, DCATAP, DCAT. These tags will be added.

2026-06-23T14:40:35.485Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:alternatieveIdentificator has already a value for DCAT in language nl, but will be overwritten.

2026-06-23T14:40:35.485Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:contactinformatie): DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.485Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:contactinformatie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.485Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:endpointURL): DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.485Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:endpointURL has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.486Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:endpointbeschrijving): DCAT, DCATAP, GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.486Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:endpointbeschrijving has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.486Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:landingspagina): DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.486Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:landingspaginaVoorAuthenticatie): GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.487Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:identificator): reuse, DCAT. These tags will be added.

2026-06-23T14:40:35.487Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:titel has already a value for ap-usageNote-nl in language nl, but will be overwritten.

2026-06-23T14:40:35.487Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:titel): GEODCATAP, reuse, DCATAP. These tags will be added.

2026-06-23T14:40:35.487Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:titel).

2026-06-23T14:40:35.487Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:beschrijving): GEODCATAP, reuse, DCATAP. These tags will be added.

2026-06-23T14:40:35.487Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:beschrijving).

2026-06-23T14:40:35.487Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:contactinformatie): GEODCATAP, reuse, DCAT. These tags will be added.

2026-06-23T14:40:35.488Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:levensfase): reuse. These tags will be added.

2026-06-23T14:40:35.488Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:toegankelijkheid): DCAT, DCATAP, GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.488Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:toegankelijkheid has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.488Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:identificator): DCAT, reuse. These tags will be added.

2026-06-23T14:40:35.488Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Agent:naam): GEODCATAP, DCATAP. These tags will be added.

2026-06-23T14:40:35.488Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Agent:naam).

2026-06-23T14:40:35.489Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:licentie): GEODCATAP, reuse, DCATAP. These tags will be added.

2026-06-23T14:40:35.489Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:alternatieve idenficator): DCAT, DCATAP. These tags will be added.

2026-06-23T14:40:35.489Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Catalogus:alternatieve idenficator has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.489Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:versie): DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.489Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:versie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.489Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:landingspaginaVoorStatusinformatie): GEODCATAP. These tags will be added.

2026-06-23T14:40:35.489Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:rechten): reuse, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.490Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord:bron metadata record landingspagina): reuse, parent. These tags will be added.

2026-06-23T14:40:35.490Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord:bron metadata record landingspagina has an empty value for tag parent.

2026-06-23T14:40:35.490Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:belanghebbendewetgeving): property-usage-scope, reuse, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.490Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:beschrijving): property-usage-scope, DCAT, DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.490Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:beschrijving has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.491Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord:alternatieve identificator): GEODCATAP, reuse, DCAT, DCATAP. These tags will be added.

2026-06-23T14:40:35.491Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord:alternatieve identificator has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.491Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Identificator:gestructureerdeIdentificator): reuse. These tags will be added.

2026-06-23T14:40:35.491Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Identificator:gestructureerdeIdentificator).

2026-06-23T14:40:35.491Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Identificator:identificator): DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.491Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Identificator:identificator).

2026-06-23T14:40:35.491Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Identificator:toegekendDoor): reuse. These tags will be added.

2026-06-23T14:40:35.491Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Identificator:toegekendDoorString): reuse. These tags will be added.

2026-06-23T14:40:35.491Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-Generiek:Identificator:toegekendOp): reuse. These tags will be added.

2026-06-23T14:40:35.492Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Contactinfo:e-mail): GEODCATAP. These tags will be added.

2026-06-23T14:40:35.492Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:alternatieve identificator): DCAT, DCATAP. These tags will be added.

2026-06-23T14:40:35.492Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:alternatieve identificator has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.492Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:alternatieve Identificator): DCAT, DCATAP. These tags will be added.

2026-06-23T14:40:35.492Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:alternatieve Identificator has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.492Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord:identificator): GEODCATAP, reuse, DCAT. These tags will be added.

2026-06-23T14:40:35.492Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord:aanmaakdatum): GEODCATAP, DCATAP. These tags will be added.

2026-06-23T14:40:35.493Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord:titel): GEODCATAP, DCATAP. These tags will be added.

2026-06-23T14:40:35.493Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord:titel).

2026-06-23T14:40:35.493Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:beschrijving): GEODCATAP, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.493Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:beschrijving).

2026-06-23T14:40:35.493Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:alternatieve identificator): reuse, DCAT, DCATAP. These tags will be added.

2026-06-23T14:40:35.493Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:alternatieve identificator has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.493Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord:wijzigingsdatum): GEODCATAP, DCATAP. These tags will be added.

2026-06-23T14:40:35.493Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:toegankelijkheid): DCAT, DCATAP, GEODCATAP, reuse, ap-usage-nl. These tags will be added.

2026-06-23T14:40:35.493Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:toegankelijkheid has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.493Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:toegankelijkheid has already a value for ap-usage-nl in language nl, but will be overwritten.

2026-06-23T14:40:35.494Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:conform): DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.494Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:versie): DCAT, reuse. These tags will be added.

2026-06-23T14:40:35.494Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:identificator): DCAT. These tags will be added.

2026-06-23T14:40:35.494Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:beschrijving): DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.494Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:beschrijving has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.494Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:beschrijving).

2026-06-23T14:40:35.494Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:conform aan protocol): DCATAP, GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.494Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:trefwoord): DCAT, DCATAP, GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.495Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:trefwoord has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.495Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:trefwoord).

2026-06-23T14:40:35.495Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord:conform): reuse, GEODCATAP, DCATAP. These tags will be added.

2026-06-23T14:40:35.495Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:contactinformatie): reuse, DCAT, property-usage-scope, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.495Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:contactinformatie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.495Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:ruimtelijkVoorstellingsType): GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.495Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:VoorbeeldWeergave:titel).

2026-06-23T14:40:35.496Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:VoorbeeldWeergave:beschrijving).

2026-06-23T14:40:35.496Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:voorbeeldweergave): DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.496Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:formaat): DCAT, DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.496Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:formaat has an empty value for tag DCAT.

2026-06-23T14:40:35.496Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:RelatieQualificatie:rol): DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.496Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:RelatieQualificatie:rol has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.497Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:statuut): reuse. These tags will be added.

2026-06-23T14:40:35.497Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:statuut): reuse. These tags will be added.

2026-06-23T14:40:35.497Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:identificator): property-usage-scope, reuse, DCAT, DCATAP. These tags will be added.

2026-06-23T14:40:35.497Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:identificator has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.497Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:periodiciteit): DCAT, property-usage-scope, reuse, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.497Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:periodiciteit has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.498Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Frequency): class-usage-scope. These tags will be added.

2026-06-23T14:40:35.498Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:publicatiedatum): reuse, DCAT, property-usage-scope, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.498Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:publicatiedatum has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.499Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:temporeledekking): DCAT, property-usage-scope, reuse, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.499Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:temporeledekking has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.499Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:titel): DCAT, property-usage-scope, reuse, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.499Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:titel has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.499Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:wijzigingsdatum): property-usage-scope, reuse, DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.499Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:wijzigingsdatum has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.500Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:dct:PeriodOfTime:dcat:endDate): reuse, property-usage-scope, DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.500Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:dct:PeriodOfTime:dcat:endDate has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.500Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:dct:PeriodOfTime:dcat:startDate): DCATAP, property-usage-scope, reuse, DCAT, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.500Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:dct:PeriodOfTime:dcat:startDate has already a value for DCAT in language nl, but will be overwritten.

2026-06-23T14:40:35.500Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:dct:PeriodOfTime:time:hasBeginning): DCATAP, reuse, DCAT, property-usage-scope, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.501Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:dct:PeriodOfTime:time:hasBeginning has already a value for DCAT in language nl, but will be overwritten.

2026-06-23T14:40:35.501Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:dct:PeriodOfTime:time:hasEnd): DCATAP, DCAT, property-usage-scope, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.501Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:dct:PeriodOfTime:time:hasEnd has already a value for DCAT in language nl, but will be overwritten.

2026-06-23T14:40:35.501Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:trefwoord): DCAT, GEODCATAP, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.501Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:trefwoord has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.501Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:trefwoord).

2026-06-23T14:40:35.501Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:landingspaginaVoorGebruiksinformatie): GEODCATAP. These tags will be added.

2026-06-23T14:40:35.502Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:thema): DCAT, DCATAP, GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.502Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:thema has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.502Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:landingspagina): DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.502Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:titel): GEODCATAP, DCATAP. These tags will be added.

2026-06-23T14:40:35.502Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:titel).

2026-06-23T14:40:35.502Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:titel): DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.502Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:titel).

2026-06-23T14:40:35.502Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:licentie): DCAT, DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.502Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:licentie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.503Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:titel): GEODCATAP, DCAT, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.503Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:titel has an empty value for tag DCAT.

2026-06-23T14:40:35.503Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:titel).

2026-06-23T14:40:35.503Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:identificator): DCAT, GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.503Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:rechten): DCAT, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.503Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:thema): DCAT, DCATAP, GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.503Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:thema has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.503Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:licentie): DCAT, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.504Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:publicatiedatum): DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.504Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:publicatiedatum has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.504Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:geografischedekking): DCATAP, DCAT, reuse, property-usage-scope, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.504Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DatasetSerie:geografischedekking has already a value for DCAT in language nl, but will be overwritten.

2026-06-23T14:40:35.504Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Plaats:geometrie): DCAT, DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.504Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Plaats:geometrie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.505Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Plaats:boundingBox): DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.505Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Plaats:boundingBox has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.505Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Plaats:Centroid): DCAT, DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.505Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Plaats:Centroid has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.506Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Plaats:plaatsnaam): reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.506Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Plaats:plaatsnaam).

2026-06-23T14:40:35.506Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:ruimtelijkeResolutie): GEODCATAP, DCATAP. These tags will be added.

2026-06-23T14:40:35.509Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Resolutie:waarde): GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.510Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Resolutie:resolutiemethode): GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.510Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:INSPIREthema): reuse. These tags will be added.

2026-06-23T14:40:35.511Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:servicetype): GEODCATAP. These tags will be added.

2026-06-23T14:40:35.511Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:servicecategorie): GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.511Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:conform): DCAT, DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.511Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:conform has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.511Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Standaard:titel).

2026-06-23T14:40:35.511Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Standaard:beschrijving): DCAT. These tags will be added.

2026-06-23T14:40:35.512Z error: [AttributeConverterHandler]: Unable to determine the range for attribute (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Standaard:beschrijving).

2026-06-23T14:40:35.512Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:CatalogusRecord:bron metadata record): reuse, GEODCATAP, DCATAP. These tags will be added.

2026-06-23T14:40:35.513Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:herkomst): reuse. These tags will be added.

2026-06-23T14:40:35.513Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:downloadURL has already a value for ap-usageNote-nl in language nl, but will be overwritten.

2026-06-23T14:40:35.513Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:downloadURL): DCAT, DCATAP, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.513Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:downloadURL has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.514Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:toegangsURL has already a value for ap-usageNote-nl in language nl, but will be overwritten.

2026-06-23T14:40:35.514Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:toegangsURL): DCAT, DCATAP, GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.514Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Distributie:toegangsURL has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.514Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:contactinformatie): DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.514Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:contactinformatie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.514Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:wijzigingdatum): DCAT, DCATAP, GEODCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.514Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:wijzigingdatum has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.514Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:creatiedatum): GEODCATAP. These tags will be added.

2026-06-23T14:40:35.515Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:creatiedatum): GEODCATAP. These tags will be added.

2026-06-23T14:40:35.515Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:publicatiedatum): DCAT, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.515Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:wijzigingsdatum): DCAT, reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.515Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:geografischeDekking): DCAT, DCATAP, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.515Z warn: [ConverterHandler]: Entity with path Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:Dataset:geografischeDekking has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.515Z info: [ElementConverterHandler]: Unknown tags for element (Model:Domain Model:OSLO²_vocabularium:OSLO-metadataVoorServices:DataService:geografischeDekking): GEODCATAP. These tags will be added.

2026-06-23T14:40:35.516Z info: [ElementConverterHandler]: Unknown tags for element (hoofdonderwerp): GEODCATAP, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.517Z info: [ElementConverterHandler]: Unknown tags for element (hoofdonderwerp): GEODCATAP, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.517Z info: [ElementConverterHandler]: Unknown tags for element (record): GEODCATAP, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.517Z info: [ElementConverterHandler]: Unknown tags for element (record): GEODCATAP, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.517Z info: [ElementConverterHandler]: Unknown tags for element (uitgever): GEODCATAP, DCAT. These tags will be added.

2026-06-23T14:40:35.517Z info: [ElementConverterHandler]: Unknown tags for element (uitgever): GEODCATAP, DCAT. These tags will be added.

2026-06-23T14:40:35.518Z info: [ElementConverterHandler]: Unknown tags for element (biedtInformatieAanOver): GEODCATAP, DCAT, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.518Z warn: [ConverterHandler]: Entity with path biedtInformatieAanOver has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.518Z info: [ElementConverterHandler]: Unknown tags for element (biedtInformatieAanOver): GEODCATAP, DCAT, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.518Z warn: [ConverterHandler]: Entity with path biedtInformatieAanOver has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.518Z info: [ElementConverterHandler]: Unknown tags for element (wordtAangebodenDoor): GEODCATAP, DCAT, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.518Z warn: [ConverterHandler]: Entity with path wordtAangebodenDoor has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.518Z info: [ElementConverterHandler]: Unknown tags for element (wordtAangebodenDoor): GEODCATAP, DCAT, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.518Z warn: [ConverterHandler]: Entity with path wordtAangebodenDoor has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.519Z info: [ElementConverterHandler]: Unknown tags for element (uitgever): GEODCATAP, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.519Z info: [ElementConverterHandler]: Unknown tags for element (uitgever): GEODCATAP, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.519Z info: [ElementConverterHandler]: Unknown tags for element (heeftDataset): GEODCATAP, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.519Z info: [ElementConverterHandler]: Unknown tags for element (heeftDataset): GEODCATAP, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.519Z info: [ElementConverterHandler]: Unknown tags for element (distributie): GEODCATAP, DCAT, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.519Z warn: [ConverterHandler]: Entity with path distributie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.519Z info: [ElementConverterHandler]: Unknown tags for element (distributie): GEODCATAP, DCAT, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.519Z warn: [ConverterHandler]: Entity with path distributie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.520Z info: [ElementConverterHandler]: Unknown tags for element (heeftDataService): GEODCATAP, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.520Z info: [ElementConverterHandler]: Unknown tags for element (heeftDataService): GEODCATAP, DCATAP, reuse. These tags will be added.

2026-06-23T14:40:35.520Z info: [ElementConverterHandler]: Unknown tags for element (eigenaar): GEODCATAP, reuse, property-usage-scope. These tags will be added.

2026-06-23T14:40:35.520Z info: [ElementConverterHandler]: Unknown tags for element (eigenaar): GEODCATAP, reuse, property-usage-scope. These tags will be added.

2026-06-23T14:40:35.520Z info: [ElementConverterHandler]: Unknown tags for element (verdeler): reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.520Z info: [ElementConverterHandler]: Unknown tags for element (verdeler): reuse, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.521Z info: [ElementConverterHandler]: Unknown tags for element (inserie): DCAT, DCATAP, reuse, property-usage-scope, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.521Z warn: [ConverterHandler]: Entity with path inserie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.521Z info: [ElementConverterHandler]: Unknown tags for element (inserie): DCAT, DCATAP, reuse, property-usage-scope, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.521Z warn: [ConverterHandler]: Entity with path inserie has already a value for DCATAP in language nl, but will be overwritten.

2026-06-23T14:40:35.521Z info: [ElementConverterHandler]: Unknown tags for element (relatie): DCAT, reuse. These tags will be added.

2026-06-23T14:40:35.521Z info: [ElementConverterHandler]: Unknown tags for element (relatie): DCAT, reuse. These tags will be added.

2026-06-23T14:40:35.522Z info: [ElementConverterHandler]: Unknown tags for element (uitgever): reuse, property-usage-scope, GEODCATAP. These tags will be added.

2026-06-23T14:40:35.522Z info: [ElementConverterHandler]: Unknown tags for element (uitgever): reuse, property-usage-scope, GEODCATAP. These tags will be added.

#||# -------------------------------------


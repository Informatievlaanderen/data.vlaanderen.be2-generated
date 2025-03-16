#||# oslo-converter-ea for diagram OSLO-Mobiliteitsbudget

#||# -------------------------------------

2025-03-16T07:39:14.871Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Voorwaarde:(Voorwaarde -> Mobiliteitsbudget) has no name. Ignoring this connector.

2025-03-16T07:39:14.873Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Persoon:Persoon:(Persoon -> Agent) is not an association with a source role. Ignoring this connector.

2025-03-16T07:39:14.873Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteit-Trips-En-Aanbod:Vervoersbewijs:(Vervoersbewijs -> Mobiliteitsdienst) has no name. Ignoring this connector.

2025-03-16T07:39:14.874Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteit-Trips-En-Aanbod:Mobiliteitsdienst:Omvat is not an association with a source role. Ignoring this connector.

2025-03-16T07:39:14.874Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteit-Trips-En-Aanbod:Reiziger:IsMedereizigerVan is not an association with a source role. Ignoring this connector.

2025-03-16T07:39:14.874Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteit-Trips-En-Aanbod:Reiziger:(Reiziger -> Vervoersbewijs) is not an association with a source role. Ignoring this connector.

2025-03-16T07:39:14.874Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteit-Trips-En-Aanbod:Reis:(Reis -> Vervoersbewijs) has no name. Ignoring this connector.

2025-03-16T07:39:14.874Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteit-Trips-En-Aanbod:Reiziger:(Reiziger -> Reis) is not an association with a source role. Ignoring this connector.

2025-03-16T07:39:14.875Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteit-Trips-En-Aanbod:Reis:IsDeelVan is not an association with a source role. Ignoring this connector.

2025-03-16T07:39:14.875Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Consumptie:(Consumptie -> Mobiliteitsdienst) has no name. Ignoring this connector.

2025-03-16T07:39:14.875Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Mobiliteitsbudget:(Mobiliteitsbudget -> Consumptie) has no name. Ignoring this connector.

2025-03-16T07:39:14.875Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Persoon:Persoon:heeftRelatieMet is not an association with a source role. Ignoring this connector.

2025-03-16T07:39:14.876Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Mobiliteitsbudget:(Mobiliteitsbudget -> Agent) has no name. Ignoring this connector.

2025-03-16T07:39:14.876Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Organisatie:Organisatie:(Organisatie -> Agent) is not an association with a source role. Ignoring this connector.

2025-03-16T07:39:14.876Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteit-Trips-En-Aanbod:Reiziger:(Reiziger -> Agent) is not an association with a source role. Ignoring this connector.

2025-03-16T07:39:14.876Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Generiek:Agent:(Agent -> Mobiliteitsbudget) has no name. Ignoring this connector.

2025-03-16T07:39:14.876Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:W3C-Time:Moment:(Moment -> TemporeleEntiteit) is not an association with a source role. Ignoring this connector.

2025-03-16T07:39:14.876Z info: Connector Model:applicatieprofiel_OSLO-Mobiliteitsbudget:W3C-Time:Periode:(Periode -> TemporeleEntiteit) is not an association with a source role. Ignoring this connector.

2025-03-16T07:39:14.877Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model) and fallback URI (http://todo.com/) will be assigned.

2025-03-16T07:39:14.877Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:applicatieprofiel_OSLO-Mobiliteitsbudget) and fallback URI (http://todo.com/) will be assigned.

2025-03-16T07:39:14.877Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Organisatie:OSLO²_usecase_Organisatie_publiekeOrganisatie) and fallback URI (http://todo.com/) will be assigned.

2025-03-16T07:39:14.877Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Persoon:OSLO²_usecase_Persoon_identificatiePersoon) and fallback URI (http://todo.com/) will be assigned.

2025-03-16T07:39:14.877Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:applicatieprofiel_OSLO-Mobiliteitsbudget:W3C-Time) and fallback URI (http://todo.com/) will be assigned.

2025-03-16T07:39:14.877Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Incentiveringsplatform) and fallback URI (http://todo.com/) will be assigned.

2025-03-16T07:39:14.877Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-ObservatiesEnMetingen) and fallback URI (http://todo.com/) will be assigned.

2025-03-16T07:39:14.880Z warn: [ConnectorConverterHandler]: Connector (Omvat) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-03-16T07:39:14.881Z warn: [ConnectorConverterHandler]: Connector (vervoersbewijs) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-03-16T07:39:14.881Z warn: [ConnectorConverterHandler]: Connector (dienst) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-03-16T07:39:14.881Z warn: [ConnectorConverterHandler]: Connector (consumptie) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-03-16T07:39:14.881Z warn: [ConnectorConverterHandler]: Connector (IsMedereizigerVan (target)) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-03-16T07:39:14.881Z warn: [ConnectorConverterHandler]: Connector (IsMedereizigerVan (source)) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-03-16T07:39:14.881Z warn: [ConnectorConverterHandler]: Connector (vervoersbewijs) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-03-16T07:39:14.881Z warn: [ConnectorConverterHandler]: Connector (onderneemt) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-03-16T07:39:14.881Z warn: [ConnectorConverterHandler]: Connector (mobiliteitsbudget) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-03-16T07:39:14.881Z warn: [ConnectorConverterHandler]: Connector (heeftRelatieMet) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-03-16T07:39:14.881Z warn: [ConnectorConverterHandler]: Connector (Persoon (source)) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-03-16T07:39:14.881Z warn: [ConnectorConverterHandler]: Connector (Persoon (target)) does not have a package tag defined. Trying to determine the correct base URI based on the source and destination objects their package.

2025-03-16T07:39:14.883Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Mobiliteitsbudget has an empty value for tag usageNote-nl.

2025-03-16T07:39:14.883Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Organisatie:OrganisatieStatus has an empty value for tag ap-usageNote-nl.

2025-03-16T07:39:14.884Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Waardetype has an empty value for tag usageNote-nl.

2025-03-16T07:39:14.884Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteit-Trips-En-Aanbod:Reiziger has an empty value for tag usageNote-nl.

2025-03-16T07:39:14.884Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteit-Trips-En-Aanbod:Vervoermiddel has an empty value for tag usageNote-nl.

2025-03-16T07:39:14.885Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteit-Trips-En-Aanbod:Dienstverleningtype has an empty value for tag usageNote-nl.

2025-03-16T07:39:14.885Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Organisatie:Organisatie has an empty value for tag ap-usageNote-nl.

2025-03-16T07:39:14.885Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Organisatie:OrganisatieClassificatie has an empty value for tag ap-usageNote-nl.

2025-03-16T07:39:14.885Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Organisatie:OrganisatieType has an empty value for tag ap-usageNote-nl.

2025-03-16T07:39:14.886Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Organisatie:OrganisatieActiviteit has an empty value for tag ap-usageNote-nl.

2025-03-16T07:39:14.887Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Mobiliteitsbudget:type has an empty value for tag usageNote-nl.

2025-03-16T07:39:14.887Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Mobiliteitsbudget:vervaldatum has an empty value for tag usageNote-nl.

2025-03-16T07:39:14.890Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Mobiliteitsbudget:toegekendOp has an empty value for tag usageNote-nl.

2025-03-16T07:39:14.890Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Mobiliteitsbudget:naam has an empty value for tag usageNote-nl.

2025-03-16T07:39:14.890Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Mobiliteitsbudget:waarde has an empty value for tag usageNote.

2025-03-16T07:39:14.891Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Mobiliteitsbudget:waardetype has an empty value for tag usageNote-nl.

2025-03-16T07:39:14.891Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Generiek:Agent:segment has an empty value for tag usageNote-nl.

2025-03-16T07:39:14.891Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Mobiliteitsbudget:begindatum has an empty value for tag usageNote-nl.

2025-03-16T07:39:14.892Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Persoon:Geslacht has an empty value for tag ap-usageNote-nl.

2025-03-16T07:39:14.897Z warn: [ConverterHandler]: Entity with path Model:applicatieprofiel_OSLO-Mobiliteitsbudget:OSLO-Mobiliteitsbudget:Segment:waarde has an empty value for tag usageNote-nl.

#||# -------------------------------------


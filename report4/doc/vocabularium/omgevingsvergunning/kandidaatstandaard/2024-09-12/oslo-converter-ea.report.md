2024-09-16T12:35:08.817Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.818Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:W3C) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.818Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:W3C:PROV) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.819Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:W3C:xsd) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.819Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:OGC) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.819Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (SEMIC:CPSV) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.819Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (EUPO:CDM) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.819Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:OSLO-Omgevingsvergunning:visualization) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.819Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:OGC:geosparql) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.819Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (OSLO:OSLO-Persoon:OSLO²_usecase_Persoon_identificatiePersoon) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.819Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:EUPO) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.819Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:EUPO:ELI) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.820Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:W3C:SKOS) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.820Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:OSLO) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.820Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:W3C:time) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.820Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:OSLO:OSLO-Recht) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.820Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:SEMIC) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.820Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:SEMIC:ADMS) and fallback URI (http://todo.com/) will be assigned.

2024-09-16T12:35:08.820Z warn: [PackageConverterHandler]: No value found for tag "baseUri" in package (Model:OSLO:OSLO-Slim-Ruimtelijk-Plannen) and fallback URI (http://todo.com/) will be assigned.

/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/ElementConverterHandler.js:129

                throw new Error(`[ElementConverterHandler]: Unable to find parent object for class (${object.path}).`);

                      ^



Error: [ElementConverterHandler]: Unable to find parent object for class (Model:OSLO-Omgevingsvergunning:Rechtshandeling).

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/ElementConverterHandler.js:129:23

    at Array.forEach (<anonymous>)

    at ElementConverterHandler.getParentInformationQuads (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/ElementConverterHandler.js:126:31)

    at ElementConverterHandler.createQuads (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/ElementConverterHandler.js:97:28)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/ElementConverterHandler.js:28:52

    at Array.forEach (<anonymous>)

    at ElementConverterHandler.convert (/usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/converter-handlers/ElementConverterHandler.js:28:14)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:42:31

    at Array.map (<anonymous>)

    at /usr/local/lib/node_modules/@oslo-flanders/ea-converter/lib/ConverterHandlerService.js:42:18



Node.js v20.15.1


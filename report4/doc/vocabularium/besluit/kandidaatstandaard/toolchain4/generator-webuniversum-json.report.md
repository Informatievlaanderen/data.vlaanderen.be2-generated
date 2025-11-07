#||# oslo-webuniversum-json-generator for language nl  

#||# -------------------------------------  

2025-11-07T11:43:22.443Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/prov#wasDerivedFrom which acts as a parent. Using original URI as fallback.

2025-11-07T11:43:22.445Z warn: Unable to find the assigned URI for external class http://www.w3.org/2004/02/skos/core#Concept which acts as a parent. Using original URI as fallback.

2025-11-07T11:43:22.460Z warn: Unable to find the assigned URI for external class http://schema.org/ListItem which acts as a parent. Using original URI as fallback.

2025-11-07T11:43:22.464Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#locatorDesignator which acts as a parent. Using original URI as fallback.

2025-11-07T11:43:22.464Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#locatorDesignator which acts as a parent. Using original URI as fallback.

2025-11-07T11:43:22.465Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#postName which acts as a parent. Using original URI as fallback.

2025-11-07T11:43:22.465Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#adminUnitL1 which acts as a parent. Using original URI as fallback.

2025-11-07T11:43:22.467Z warn: Unable to find the assigned URI for external class http://xmlns.com/foaf/0.1/Document which acts as a parent. Using original URI as fallback.

Error: Unable to find the assigned URI for range urn:oslo-toolchain:dcf9bcb08e7818e699bb11b17bdb7411cb1d9fa86c4849b77627a2c05c5c1488 of attribute [urn:oslo-toolchain:a6879f19a6d494dd457f627f400753abeb488523f779c968a95a945d7a71fc9c](all-mobiliteit.jsonld#L4162).

    at JsonWebuniversumGenerationService.addPropertySpecificInformation (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270:19)

    at /usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:190:95

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)

    at async Promise.all (index 4)

    at async JsonWebuniversumGenerationService.generateEntityData (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:192:32)

    at async Promise.all (index 2)

    at async JsonWebuniversumGenerationService.run (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:38:25)

/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270

            throw new Error(`Unable to find the assigned URI for range ${range.value} of attribute ${subject.value}.`);

                  ^



Error: Unable to find the assigned URI for range urn:oslo-toolchain:3e5fda4625c16018be3b2864201eea8fd1687c8c3d6b1424fa5e2fa5a4dc9e83 of attribute [urn:oslo-toolchain:08ba811ebb8f7db43728df35a32f88a4ae305aa655dbdb900a6ca5fb176f4e3d](all-mobiliteit.jsonld#L3105).

    at JsonWebuniversumGenerationService.addPropertySpecificInformation (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270:19)

    at /usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:190:95

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)

    at async Promise.all (index 1)

    at async JsonWebuniversumGenerationService.generateEntityData (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:192:32)



Node.js v20.15.0


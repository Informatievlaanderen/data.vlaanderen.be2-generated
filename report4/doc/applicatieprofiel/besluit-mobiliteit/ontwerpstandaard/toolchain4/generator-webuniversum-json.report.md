#||# oslo-webuniversum-json-generator for language nl  

#||# -------------------------------------  

2025-03-17T20:57:39.354Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/prov#Activity which acts as a parent. Using original URI as fallback.

2025-03-17T20:57:39.363Z warn: Unable to find the assigned URI for external class http://www.w3.org/2004/02/skos/core#Concept which acts as a parent. Using original URI as fallback.

2025-03-17T20:57:39.383Z warn: Unable to find the assigned URI for external class http://xmlns.com/foaf/0.1/Document which acts as a parent. Using original URI as fallback.

Error: Unable to find the assigned URI for range http://www.w3.org/2001/XMLSchema#boolean of attribute [urn:oslo-toolchain:22f78e195aef2704ee9e006e0c6f5e29581add7914f4d0c751ed4a318c5f18cb](all-besluit-mobiliteit-ap.jsonld#L4476).

    at JsonWebuniversumGenerationService.addPropertySpecificInformation (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:202:19)

    at /usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:181:96

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)

/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:202

            throw new Error(`Unable to find the assigned URI for range ${range.value} of attribute ${subject.value}.`);

                  ^



Error: Unable to find the assigned URI for range http://www.w3.org/1999/02/22-rdf-syntax-ns#HTML of attribute [urn:oslo-toolchain:60a9371b838d44ad996c4c0da2424a832424e2e87339dd16689930c297912464](all-besluit-mobiliteit-ap.jsonld#L4508).

    at JsonWebuniversumGenerationService.addPropertySpecificInformation (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:202:19)

    at /usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:181:96

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)



Node.js v20.15.0


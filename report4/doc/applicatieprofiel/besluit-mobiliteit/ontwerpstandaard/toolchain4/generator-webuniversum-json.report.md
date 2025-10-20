#||# oslo-webuniversum-json-generator for language nl  

#||# -------------------------------------  

2025-10-20T16:22:31.573Z warn: Unable to find the assigned URI for external class http://www.w3.org/2004/02/skos/core#Concept which acts as a parent. Using original URI as fallback.

2025-10-20T16:22:31.603Z warn: Unable to find the assigned URI for external class http://schema.org/ListItem which acts as a parent. Using original URI as fallback.

2025-10-20T16:22:31.606Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#locatorDesignator which acts as a parent. Using original URI as fallback.

2025-10-20T16:22:31.606Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#locatorDesignator which acts as a parent. Using original URI as fallback.

2025-10-20T16:22:31.607Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#postName which acts as a parent. Using original URI as fallback.

2025-10-20T16:22:31.608Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#adminUnitL1 which acts as a parent. Using original URI as fallback.

2025-10-20T16:22:31.609Z warn: Unable to find the assigned URI for external class http://xmlns.com/foaf/0.1/Document which acts as a parent. Using original URI as fallback.

Error: Unable to find the assigned URI for range urn:oslo-toolchain:4387492f3a65a8c4bcc134c1aca977a941a4e63a6d7f4242c57813044ddb3573 of attribute [urn:oslo-toolchain:d36afb27557d439549efc2d104ea709e0be651ea5c6fe8f3e2374a66e34f998e](all-besluit-mobiliteit-ap.jsonld#L3315).

    at JsonWebuniversumGenerationService.addPropertySpecificInformation (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270:19)

    at /usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:190:95

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)

    at async Promise.all (index 2)

    at async JsonWebuniversumGenerationService.generateEntityData (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:192:32)

    at async Promise.all (index 6)

    at async JsonWebuniversumGenerationService.run (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:38:25)

/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270

            throw new Error(`Unable to find the assigned URI for range ${range.value} of attribute ${subject.value}.`);

                  ^



Error: Unable to find the assigned URI for range urn:oslo-toolchain:3e5fda4625c16018be3b2864201eea8fd1687c8c3d6b1424fa5e2fa5a4dc9e83 of attribute [urn:oslo-toolchain:08ba811ebb8f7db43728df35a32f88a4ae305aa655dbdb900a6ca5fb176f4e3d](all-besluit-mobiliteit-ap.jsonld#L2775).

    at JsonWebuniversumGenerationService.addPropertySpecificInformation (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270:19)

    at /usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:190:95

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)

    at async Promise.all (index 1)

    at async JsonWebuniversumGenerationService.generateEntityData (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:192:32)



Node.js v20.15.0


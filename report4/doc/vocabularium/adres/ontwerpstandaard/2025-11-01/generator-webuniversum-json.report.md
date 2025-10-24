#||# oslo-webuniversum-json-generator for language nl  

#||# -------------------------------------  

2025-10-24T07:05:01.457Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#geometry which acts as a parent. Using original URI as fallback.

2025-10-24T07:05:01.477Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#locatorDesignator which acts as a parent. Using original URI as fallback.

2025-10-24T07:05:01.478Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#postName which acts as a parent. Using original URI as fallback.

2025-10-24T07:05:01.478Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#locatorDesignator which acts as a parent. Using original URI as fallback.

2025-10-24T07:05:01.478Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#adminUnitL1 which acts as a parent. Using original URI as fallback.

Error: Unable to find the assigned URI for range urn:oslo-toolchain:fb12f40627ad6be1e5fc69eca3011bac84f8d9f99626f9bd4852dba7f34ea377 of attribute [urn:oslo-toolchain:9c80d14a1be1882208a84a4c970ea1dcc32b398956e083f078e214e459b32261](all-adres.jsonld#L2891).

    at JsonWebuniversumGenerationService.addPropertySpecificInformation (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270:19)

    at /usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:190:95

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)

    at async Promise.all (index 2)

    at async JsonWebuniversumGenerationService.generateEntityData (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:192:32)

    at async Promise.all (index 0)

    at async JsonWebuniversumGenerationService.run (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:38:25)

/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270

            throw new Error(`Unable to find the assigned URI for range ${range.value} of attribute ${subject.value}.`);

                  ^



Error: Unable to find the assigned URI for range urn:oslo-toolchain:949ce5b2081e6f30812d87cf2b54bc388810d5f9b845902ec495660ff3074011 of attribute [urn:oslo-toolchain:5a8ef9a2abdab920c196c139b64f2a8a37ead31e7b6cbd3b10671879e7e9bdd5](all-adres.jsonld#L2169).

    at JsonWebuniversumGenerationService.addPropertySpecificInformation (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270:19)

    at /usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:190:95

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)

    at async Promise.all (index 1)

    at async JsonWebuniversumGenerationService.generateEntityData (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:192:32)



Node.js v20.15.0


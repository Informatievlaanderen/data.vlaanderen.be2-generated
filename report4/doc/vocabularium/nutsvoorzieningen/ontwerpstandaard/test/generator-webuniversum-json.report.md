#||# oslo-webuniversum-json-generator for language nl  

#||# -------------------------------------  

2025-11-20T16:50:16.683Z warn: Unable to find the assigned URI for external class http://def.isotc211.org/iso19157/2013/DataQuality_2#DQ_Element which acts as a parent. Using original URI as fallback.

2025-11-20T16:50:16.705Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#locatorDesignator which acts as a parent. Using original URI as fallback.

2025-11-20T16:50:16.706Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#postName which acts as a parent. Using original URI as fallback.

2025-11-20T16:50:16.706Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#adminUnitL1 which acts as a parent. Using original URI as fallback.

2025-11-20T16:50:16.707Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#locatorDesignator which acts as a parent. Using original URI as fallback.

Error: Unable to find the assigned URI for range urn:oslo-toolchain:f6f61ca86463e86cf98e95067c1650b48d0921593e38e244493486c2a495a74d of attribute [urn:oslo-toolchain:eec88fd4e9bb62011c5e6bde0b4a88eb23ab95a0cf2575e64651f26a2c1d28bc](all-nutsvoorzieningen.jsonld#L7014).

    at JsonWebuniversumGenerationService.addPropertySpecificInformation (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270:19)

    at /usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:190:95

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)

    at async Promise.all (index 3)

    at async JsonWebuniversumGenerationService.generateEntityData (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:192:32)

    at async Promise.all (index 0)

    at async JsonWebuniversumGenerationService.run (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:38:25)

/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270

            throw new Error(`Unable to find the assigned URI for range ${range.value} of attribute ${subject.value}.`);

                  ^



Error: Unable to find the assigned URI for range urn:oslo-toolchain:ad9bd378c3c84b7c7f9bfcd9144bf99fcb6d21758ff550d92e5cbc045111dc23 of attribute [urn:oslo-toolchain:50ab65169eea7808fc0567e12ba7b3da7e94459e473e8853e8b8f7c8063b4f36](all-nutsvoorzieningen.jsonld#L11672).

    at JsonWebuniversumGenerationService.addPropertySpecificInformation (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270:19)

    at /usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:190:95

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)

    at async Promise.all (index 1)

    at async JsonWebuniversumGenerationService.generateEntityData (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:192:32)



Node.js v20.15.0


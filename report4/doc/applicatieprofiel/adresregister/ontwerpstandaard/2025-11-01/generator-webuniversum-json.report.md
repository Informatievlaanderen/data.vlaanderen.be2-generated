#||# oslo-webuniversum-json-generator for language nl  

#||# -------------------------------------  

2025-10-23T15:15:24.917Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#geometry which acts as a parent. Using original URI as fallback.

2025-10-23T15:15:24.928Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#locatorDesignator which acts as a parent. Using original URI as fallback.

2025-10-23T15:15:24.928Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#locatorDesignator which acts as a parent. Using original URI as fallback.

2025-10-23T15:15:24.930Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#postName which acts as a parent. Using original URI as fallback.

2025-10-23T15:15:24.932Z warn: Unable to find the assigned URI for external class http://www.w3.org/ns/locn#adminUnitL1 which acts as a parent. Using original URI as fallback.

Error: Unable to find the assigned URI for range urn:oslo-toolchain:0842308883e461019be67a63c31d615663bf107094da246f872139874cb5de0c of attribute [urn:oslo-toolchain:b932a89d4508b4b915e231f445def5668cd184fc84f261670ad92d5ec62b4546](all-adressenregister.jsonld#L1300).

    at JsonWebuniversumGenerationService.addPropertySpecificInformation (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270:19)

    at /usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:190:95

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)

    at async Promise.all (index 4)

    at async JsonWebuniversumGenerationService.generateEntityData (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:192:32)

    at async Promise.all (index 3)

    at async JsonWebuniversumGenerationService.run (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:38:25)

/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270

            throw new Error(`Unable to find the assigned URI for range ${range.value} of attribute ${subject.value}.`);

                  ^



Error: Unable to find the assigned URI for range urn:oslo-toolchain:249015964cef8d0b621e5760629182afb8f21964a8d4c75687f12489949dda77 of attribute [urn:oslo-toolchain:796c2a0c87b09200f25f2d39cf1ef5b3ae22855450ae48aed1f209e209c944d0](all-adressenregister.jsonld#L1344).

    at JsonWebuniversumGenerationService.addPropertySpecificInformation (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:270:19)

    at /usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:190:95

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)

    at async Promise.all (index 1)

    at async JsonWebuniversumGenerationService.generateEntityData (/usr/local/lib/node_modules/@oslo-flanders/json-webuniversum-generator/lib/JsonWebuniversumGenerationService.js:192:32)



Node.js v20.15.0


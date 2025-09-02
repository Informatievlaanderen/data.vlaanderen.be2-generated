#||# oslo-jsonld-validator   

#||# -------------------------------------  

2025-09-02T09:30:38.942Z info: Loaded 45 URI prefixes into whitelist

2025-09-02T09:30:39.163Z warn: Found non-whitelisted assigned URI: http://schema.org/opens for subject: [urn:oslo-toolchain:ee9cfe0eea8860f9da792281e396feb6b875b51fcb29aa31a92c6019ebba8c0c](all-leermiddelen-ap.jsonld#L854)

2025-09-02T09:30:39.163Z warn: Found non-whitelisted assigned URI: http://schema.org/closes for subject: [urn:oslo-toolchain:7cc32b8548b857d89262475044d130b87584e7ec5b87119d13a3090b7756ec7f](all-leermiddelen-ap.jsonld#L892)

2025-09-02T09:30:39.163Z warn: Found non-whitelisted assigned URI: http://schema.org/dayOfWeek for subject: [urn:oslo-toolchain:0172cf620bdd16150eea25f8dc72ec563ea20d361c09f2a54a24bf5ddcbe5f25](all-leermiddelen-ap.jsonld#L930)

2025-09-02T09:30:39.163Z warn: Found non-whitelisted assigned URI: http://schema.org/validFrom for subject: [urn:oslo-toolchain:cce3ce75f91d7df4430de6592ad48ce344d910bc468607595cf07e6a2d794489](all-leermiddelen-ap.jsonld#L974)

2025-09-02T09:30:39.163Z warn: Found non-whitelisted assigned URI: http://schema.org/validThrough for subject: [urn:oslo-toolchain:78385e7b413ac08ef5a4c7306da996d075044ed0ce2852d137864303f5e43daf](all-leermiddelen-ap.jsonld#L1012)

2025-09-02T09:30:39.164Z warn: Found non-whitelisted assigned URI: http://schema.org/OpeningHoursSpecification for subject: [urn:oslo-toolchain:c35947b4ea05516bd3bdc5d373f83fca2365977e85d9c60794973d5a680a9f64](all-leermiddelen-ap.jsonld#L4162)

2025-09-02T09:30:39.166Z warn: Found a TODO or FIXME in sentence: 'TODO' for subject: [urn:oslo-toolchain:c5159c1b7585bbb69b6052999fc86aca5fbb78c3b3d7f46bea61d4cb77cbf6b6](all-leermiddelen-ap.jsonld#L4997)

2025-09-02T09:30:39.167Z warn: Found empty sentence for subject: [urn:oslo-toolchain:ee9cfe0eea8860f9da792281e396feb6b875b51fcb29aa31a92c6019ebba8c0c](all-leermiddelen-ap.jsonld#L854)

2025-09-02T09:30:39.167Z warn: Found empty sentence for subject: [urn:oslo-toolchain:7cc32b8548b857d89262475044d130b87584e7ec5b87119d13a3090b7756ec7f](all-leermiddelen-ap.jsonld#L892)

2025-09-02T09:30:39.167Z warn: Found empty sentence for subject: [urn:oslo-toolchain:cce3ce75f91d7df4430de6592ad48ce344d910bc468607595cf07e6a2d794489](all-leermiddelen-ap.jsonld#L974)

2025-09-02T09:30:39.167Z warn: Found empty sentence for subject: [urn:oslo-toolchain:78385e7b413ac08ef5a4c7306da996d075044ed0ce2852d137864303f5e43daf](all-leermiddelen-ap.jsonld#L1012)

Error: Unknown specification type: undefined

    at JsonldValidationService.validateMissingClasses (/usr/local/lib/node_modules/@oslo-flanders/jsonld-validator/lib/JsonldValidationService.js:312:27)

    at JsonldValidationService.run (/usr/local/lib/node_modules/@oslo-flanders/jsonld-validator/lib/JsonldValidationService.js:37:43)

    at /usr/local/lib/node_modules/@oslo-flanders/jsonld-validator/node_modules/@oslo-flanders/core/lib/interfaces/AppRunner.js:22:33

    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)


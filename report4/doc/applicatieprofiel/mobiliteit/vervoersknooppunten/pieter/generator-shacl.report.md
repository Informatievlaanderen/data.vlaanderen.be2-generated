#||# oslo-shacl-template-generator for language nl  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/applicatieprofiel/mobiliteit/vervoersknooppunten/pieter/merged/merged_vervoersknooppunten_nl.jsonld --language nl --output /tmp/workspace/target/doc/applicatieprofiel/mobiliteit/vervoersknooppunten/pieter/shacl/vervoersknooppunten-SHACL_nl.jsonld --shapeBaseURI https://data.dev-vlaanderen.be/doc/applicatieprofiel/mobiliteit/vervoersknooppunten/pieter# --applicationProfileURL https://data.dev-vlaanderen.be/doc/applicatieprofiel/mobiliteit/vervoersknooppunten/pieter  

2026-10-09T09:07:26.770Z warn: Unable to find the description for subject "[urn:oslo-toolchain:710dd35ccb1e7f03774cd84af7c23cfb2e1951022b0127291e6d7f9adbe55fa3](all-vervoersknooppunten.jsonld#L11212)".

2026-10-09T09:07:26.773Z warn: Unable to find the description for subject "[urn:oslo-toolchain:835aa03727b47db35664c7f2ec634976fd3f68a21106983113bb18e86a69d019](all-vervoersknooppunten.jsonld#L11568)".

2026-10-09T09:07:26.773Z warn: Unable to find the description for subject "[urn:oslo-toolchain:82c93e0a0827e4e2ee7c4e5570c8ecacad87bdb55a9f491414dc0ae04a9d39d0](all-vervoersknooppunten.jsonld#L11594)".

2026-10-09T09:07:26.793Z warn: Unable to find the description for subject "[urn:oslo-toolchain:4a01c6cda70cddc325c955b9356350360cc7b283a11e8d9f8b3515e3334d55bf](all-vervoersknooppunten.jsonld#L12720)".

#||# oslo-shacl-template-generator for language en  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/applicatieprofiel/mobiliteit/vervoersknooppunten/pieter/merged/merged_vervoersknooppunten_en.jsonld --language en --output /tmp/workspace/target/doc/applicatieprofiel/mobiliteit/vervoersknooppunten/pieter/shacl/vervoersknooppunten-SHACL_en.jsonld --shapeBaseURI https://data.dev-vlaanderen.be/doc/applicatieprofiel/mobiliteit/vervoersknooppunten/pieter# --applicationProfileURL https://data.dev-vlaanderen.be/doc/applicatieprofiel/mobiliteit/vervoersknooppunten/pieter  

Error: [ShaclTemplateGenerationService]: Unable to find the domain for subject "[[urn:oslo-toolchain:b3a16b07867e805c910f0b755aadee6620d624cd88aa6e6e9a650edbea54d579](all-vervoersknooppunten.jsonld#L14284)](all-vervoersknooppunten.jsonld#L1132)" which should act as a property.

    at ShaclTemplateGenerationService.createSubjectToShapeIdMap (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:152:31)

    at ShaclTemplateGenerationService.run (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:48:42)

    at /usr/local/lib/oslo/packages/oslo-core/lib/interfaces/AppRunner.js:37:33

    at process.processTicksAndRejections (node:internal/process/task_queues:105:5)

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/mobiliteit/vervoersknooppunten/pieter/all-vervoersknooppunten.jsonld -o /tmp/reportlines  


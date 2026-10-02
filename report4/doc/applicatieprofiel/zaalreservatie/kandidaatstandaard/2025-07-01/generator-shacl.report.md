#||# oslo-shacl-template-generator for language nl  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/2025-07-01/merged/merged_zaalreservatie_nl.jsonld --language nl --output /tmp/workspace/target/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/2025-07-01/shacl/zaalreservatie-SHACL_nl.jsonld --shapeBaseURI https://data.dev-vlaanderen.be/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/2025-07-01# --applicationProfileURL https://data.dev-vlaanderen.be/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/2025-07-01  

#||# oslo-shacl-template-generator for language en  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/2025-07-01/merged/merged_zaalreservatie_en.jsonld --language en --output /tmp/workspace/target/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/2025-07-01/shacl/zaalreservatie-SHACL_en.jsonld --shapeBaseURI https://data.dev-vlaanderen.be/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/2025-07-01# --applicationProfileURL https://data.dev-vlaanderen.be/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/2025-07-01  

Error: [ShaclTemplateGenerationService]: Unable to find the domain for subject "[urn:oslo-toolchain:aee9cfc0b4365901200e2dd99a8c558aa1f3781a11ea7fffc7591cf4494cb33f](all-zaalreservatie.jsonld#L156)" which should act as a property.

    at ShaclTemplateGenerationService.createSubjectToShapeIdMap (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:152:31)

    at ShaclTemplateGenerationService.run (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:48:42)

    at /usr/local/lib/oslo/packages/oslo-core/lib/interfaces/AppRunner.js:37:33

    at process.processTicksAndRejections (node:internal/process/task_queues:105:5)

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/2025-07-01/all-zaalreservatie.jsonld -o /tmp/reportlines  


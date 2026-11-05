#||# oslo-shacl-template-generator for language en  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter/merged/merged_cable-pipe_en.jsonld --language en --output /tmp/workspace/target/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter/shacl/cable-pipe-SHACL_en.jsonld --shapeBaseURI https://data.dev-vlaanderen.be/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter# --applicationProfileURL https://data.dev-vlaanderen.be/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter  

Error: Unable to find a label for subject "[urn:oslo-toolchain:ddcca8e662572bee4816b15dea63af4d0e7436fb42501b18f9d32fa8906f9784](all-cable-pipe.jsonld#L156)".

    at ShaclTemplateGenerationService.createSubjectToShapeIdMap (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:136:23)

    at ShaclTemplateGenerationService.run (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:48:42)

    at /usr/local/lib/oslo/packages/oslo-core/lib/interfaces/AppRunner.js:37:33

    at process.processTicksAndRejections (node:internal/process/task_queues:105:5)

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter/all-cable-pipe.jsonld -o /tmp/reportlines  


#||# oslo-shacl-template-generator for language nl  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/implementatiemodel/magda/persoon/test-full/merged/merged_persoon_nl.jsonld --language nl --output /tmp/workspace/target/doc/implementatiemodel/magda/persoon/test-full/shacl/persoon-SHACL_nl.jsonld --shapeBaseURI https://data.test-vlaanderen.be/doc/implementatiemodel/magda/persoon/test-full# --applicationProfileURL https://data.test-vlaanderen.be/doc/implementatiemodel/magda/persoon/test-full  

#||# oslo-shacl-template-generator for language en  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/implementatiemodel/magda/persoon/test-full/merged/merged_persoon_en.jsonld --language en --output /tmp/workspace/target/doc/implementatiemodel/magda/persoon/test-full/shacl/persoon-SHACL_en.jsonld --shapeBaseURI https://data.test-vlaanderen.be/doc/implementatiemodel/magda/persoon/test-full# --applicationProfileURL https://data.test-vlaanderen.be/doc/implementatiemodel/magda/persoon/test-full  

Error: [ShaclTemplateGenerationService]: Unable to find the domain for subject "[[urn:oslo-toolchain:30947190c0dcc55e46dcc8e7bf6abab0ea4531f0d4d181198b8e4435707ac417](all-persoon.jsonld#L12244)](all-persoon.jsonld#L249)" which should act as a property.

    at ShaclTemplateGenerationService.createSubjectToShapeIdMap (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:152:31)

    at ShaclTemplateGenerationService.run (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:48:42)

    at /usr/local/lib/oslo/packages/oslo-core/lib/interfaces/AppRunner.js:37:33

    at process.processTicksAndRejections (node:internal/process/task_queues:105:5)

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/implementatiemodel/magda/persoon/test-full/all-persoon.jsonld -o /tmp/reportlines  


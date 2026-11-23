#||# oslo-shacl-template-generator for language nl  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/applicatieprofiel/DigitaleWatermeter/kandidaatstandaard/pieter/merged/merged_digitale-watermeter_nl.jsonld --language nl --output /tmp/workspace/target/doc/applicatieprofiel/DigitaleWatermeter/kandidaatstandaard/pieter/shacl/digitale-watermeter-SHACL_nl.jsonld --shapeBaseURI https://data.dev-vlaanderen.be/doc/applicatieprofiel/DigitaleWatermeter/kandidaatstandaard/pieter# --applicationProfileURL https://data.dev-vlaanderen.be/doc/applicatieprofiel/DigitaleWatermeter/kandidaatstandaard/pieter  

Error: Unable to find a label for subject "[urn:oslo-toolchain:14be7390917d56b1a93d22b65ed237b78b22e6d3236bd5449cc72f5c8fa8186d](all-digitale-watermeter.jsonld#L9390)".

    at ShaclTemplateGenerationService.createSubjectToShapeIdMap (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:136:23)

    at ShaclTemplateGenerationService.run (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:49:45)

    at /usr/local/lib/oslo/packages/oslo-core/lib/interfaces/AppRunner.js:37:33

    at process.processTicksAndRejections (node:internal/process/task_queues:105:5)

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/DigitaleWatermeter/kandidaatstandaard/pieter/all-digitale-watermeter.jsonld -o /tmp/reportlines  


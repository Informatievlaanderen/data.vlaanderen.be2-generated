#||# oslo-shacl-template-generator for language nl  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/applicatieprofiel/DigitaleWatermeter/kandidaatstandaard/pieter/merged/merged_digitale-watermeter_nl.jsonld --language nl --output /tmp/workspace/target/doc/applicatieprofiel/DigitaleWatermeter/kandidaatstandaard/pieter/shacl/digitale-watermeter-SHACL_nl.jsonld --shapeBaseURI https://data.dev-vlaanderen.be/doc/applicatieprofiel/DigitaleWatermeter/kandidaatstandaard/pieter# --applicationProfileURL https://data.dev-vlaanderen.be/doc/applicatieprofiel/DigitaleWatermeter/kandidaatstandaard/pieter  

2026-11-24T11:01:19.210Z warn: Unable to find the description for subject "[urn:oslo-toolchain:71d6270d5c646a007bd29025928b66478afd1ccd1222b0d3254db1ffe2cc6f0d](all-digitale-watermeter.jsonld#L4414)".

2026-11-24T11:01:19.233Z warn: Unable to find the description for subject "[urn:oslo-toolchain:8fc45d55d3b378387c1348f553474222fcc42dd56256cd8f52c34c196e0a0dac](all-digitale-watermeter.jsonld#L8438)".

Error: Unable to find a label for the domain "urn:oslo-toolchain:047ecd14c046206c3e6122bd67238ae4d2e39eb4fc2774eb7c9664970ed7483c" of subject "[urn:oslo-toolchain:8fc45d55d3b378387c1348f553474222fcc42dd56256cd8f52c34c196e0a0dac](all-digitale-watermeter.jsonld#L8438)".

    at PropertyShapeBaseHandler.handle (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/handlers/PropertyShapeBaseHandler.js:141:23)

    at Pipeline.handle (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/types/Pipeline.js:21:28)

    at ShaclTemplateGenerationService.run (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:89:51)

    at /usr/local/lib/oslo/packages/oslo-core/lib/interfaces/AppRunner.js:37:33

    at process.processTicksAndRejections (node:internal/process/task_queues:105:5)

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/DigitaleWatermeter/kandidaatstandaard/pieter/all-digitale-watermeter.jsonld -o /tmp/reportlines  


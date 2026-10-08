#||# oslo-shacl-template-generator for language nl  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/applicatieprofiel/thermografische-gebouwanalyse/kandidaatstandaard/2025-05-22/merged/merged_thermografische-gebouwanalyse_nl.jsonld --language nl --output /tmp/workspace/target/doc/applicatieprofiel/thermografische-gebouwanalyse/kandidaatstandaard/2025-05-22/shacl/thermografische-gebouwanalyse-SHACL_nl.jsonld --shapeBaseURI https://data.dev-vlaanderen.be/doc/applicatieprofiel/thermografische-gebouwanalyse/kandidaatstandaard/2025-05-22# --applicationProfileURL https://data.dev-vlaanderen.be/doc/applicatieprofiel/thermografische-gebouwanalyse/kandidaatstandaard/2025-05-22  

Error: Child (urn:oslo-toolchain:f0f3fb64dcae681c68123f600bc1ecb2c03fae52d16d94fddb7db4841f64e7b4) or parent (urn:oslo-toolchain:ca5a1a3461de5d19666d454bd1368ebd023b49a641b5589252a6fe2e3dac75e5) domain is missing!

    at ShaclTemplateGenerationService.handleRedefinedProperties (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:195:23)

    at ShaclTemplateGenerationService.run (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:97:14)

    at /usr/local/lib/oslo/packages/oslo-core/lib/interfaces/AppRunner.js:37:33

    at process.processTicksAndRejections (node:internal/process/task_queues:105:5)

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/thermografische-gebouwanalyse/kandidaatstandaard/2025-05-22/all-thermografische-gebouwanalyse.jsonld -o /tmp/reportlines  


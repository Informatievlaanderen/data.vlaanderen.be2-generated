#||# oslo-shacl-template-generator for language nl  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/applicatieprofiel/DCAT-AP-VL/erkendestandaard/2026-02-12/merged/merged_DCAT-AP-VL_nl.jsonld --language nl --output /tmp/workspace/target/doc/applicatieprofiel/DCAT-AP-VL/erkendestandaard/2026-02-12/shacl/DCAT-AP-VL-SHACL_nl.jsonld --shapeBaseURI https://data.test-vlaanderen.be/doc/applicatieprofiel/DCAT-AP-VL/erkendestandaard/2026-02-12# --applicationProfileURL https://data.test-vlaanderen.be/doc/applicatieprofiel/DCAT-AP-VL/erkendestandaard/2026-02-12  

2026-11-24T07:48:30.384Z warn: Unable to find the description for subject "[urn:oslo-toolchain:31cf9b3d399272d7921b615f815fb152588e7f74e4f54a77df2e61f873c82cfb](all-DCAT-AP-VL.jsonld#L1173)".

2026-11-24T07:48:30.385Z warn: Unable to find the description for subject "[urn:oslo-toolchain:43353d18ad5d9be23efe3ccbcd364ad14104bd5ea65a3ffc2c4f1e07891bf730](all-DCAT-AP-VL.jsonld#L1253)".

2026-11-24T07:48:30.386Z warn: Unable to find the description for subject "[urn:oslo-toolchain:cd1a08986ade75e4719baf40c57773149a315dac2dc2d62d7bfba1439367ce4f](all-DCAT-AP-VL.jsonld#L9374)".

2026-11-24T07:48:30.386Z warn: Unable to find the description for subject "[urn:oslo-toolchain:013904af3189e8feae623d00dc7bb9c3fc4235f0964568a9c92ff9e4cc851bb2](all-DCAT-AP-VL.jsonld#L9302)".

#||# oslo-shacl-template-generator for language en  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/applicatieprofiel/DCAT-AP-VL/erkendestandaard/2026-02-12/merged/merged_DCAT-AP-VL_en.jsonld --language en --output /tmp/workspace/target/doc/applicatieprofiel/DCAT-AP-VL/erkendestandaard/2026-02-12/shacl/DCAT-AP-VL-SHACL_en.jsonld --shapeBaseURI https://data.test-vlaanderen.be/doc/applicatieprofiel/DCAT-AP-VL/erkendestandaard/2026-02-12# --applicationProfileURL https://data.test-vlaanderen.be/doc/applicatieprofiel/DCAT-AP-VL/erkendestandaard/2026-02-12  

Error: [ShaclTemplateGenerationService]: Unable to find the domain for subject "[urn:oslo-toolchain:28bf661a2db29f1b77abe7ee1056e3fd58836230478962fb256d5429f1d5b04c](all-DCAT-AP-VL.jsonld#L960)" which should act as a property.

    at ShaclTemplateGenerationService.createSubjectToShapeIdMap (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:152:31)

    at ShaclTemplateGenerationService.run (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:48:42)

    at /usr/local/lib/oslo/packages/oslo-core/lib/interfaces/AppRunner.js:37:33

    at process.processTicksAndRejections (node:internal/process/task_queues:105:5)

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/DCAT-AP-VL/erkendestandaard/2026-02-12/all-DCAT-AP-VL.jsonld -o /tmp/reportlines  


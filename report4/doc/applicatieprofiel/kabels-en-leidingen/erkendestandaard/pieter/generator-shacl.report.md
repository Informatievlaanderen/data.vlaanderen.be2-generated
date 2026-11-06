#||# oslo-shacl-template-generator for language en  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter/merged/merged_cable-pipe_en.jsonld --language en --output /tmp/workspace/target/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter/shacl/cable-pipe-SHACL_en.jsonld --shapeBaseURI https://data.dev-vlaanderen.be/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter# --applicationProfileURL https://data.dev-vlaanderen.be/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter  

2026-11-06T09:58:04.917Z warn: Unable to find the description for subject "[urn:oslo-toolchain:354c960634342862b70ac44d91762896a16260b6fcd67cd6f9dec6d336c2d004](all-cable-pipe.jsonld#L3497)".

2026-11-06T09:58:04.918Z warn: Unable to find the description for subject "[urn:oslo-toolchain:06417d7a42222edc10045142aaa9424e23abce85195c5c09a9b72631be337506](all-cable-pipe.jsonld#L3593)".

2026-11-06T09:58:04.937Z warn: Unable to find the description for subject "[urn:oslo-toolchain:a5a99efdf9a3d7efefae231ba19ebb45d9af82e06f47a4fa7247528f9af586f9](all-cable-pipe.jsonld#L7434)".

#||# oslo-shacl-template-generator for language nl  

#||# -------------------------------------  

#||# command: oslo-shacl-template-generator --input /tmp/workspace/report4/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter/merged/merged_cable-pipe_nl.jsonld --language nl --output /tmp/workspace/target/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter/shacl/cable-pipe-SHACL_nl.jsonld --shapeBaseURI https://data.dev-vlaanderen.be/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter# --applicationProfileURL https://data.dev-vlaanderen.be/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter  

Error: Unable to find a label for subject "[urn:oslo-toolchain:8876732f28508126a04b89c9d69f7e236faa41ac42c8d9f0b5227d73ef79ca80](all-cable-pipe.jsonld#L2152)".

    at ShaclTemplateGenerationService.createSubjectToShapeIdMap (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:136:23)

    at ShaclTemplateGenerationService.run (/usr/local/lib/oslo/packages/oslo-generator-shacl-template/lib/ShaclTemplateGenerationService.js:48:42)

    at /usr/local/lib/oslo/packages/oslo-core/lib/interfaces/AppRunner.js:37:33

    at process.processTicksAndRejections (node:internal/process/task_queues:105:5)

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/kabels-en-leidingen/erkendestandaard/pieter/all-cable-pipe.jsonld -o /tmp/reportlines  


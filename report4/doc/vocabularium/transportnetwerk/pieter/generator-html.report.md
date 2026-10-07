#||# oslo-generator-html for language nl  

#||# -------------------------------------  

#||# command: oslo-generator-html --input /tmp/workspace/report4/html/doc/vocabularium/transportnetwerk/pieter/html/int_transportnetwerk_nl.json --output /tmp/workspace/target/doc/vocabularium/transportnetwerk/pieter/index_nl.html --stakeholders /tmp/workspace/report4/doc/vocabularium/transportnetwerk/pieter/stakeholders.json --metadata /tmp/workspace/report4/doc/vocabularium/transportnetwerk/pieter/html/meta_transportnetwerk_nl.json --specificationType Vocabulary --specificationName --templates /tmp/workspace/report4/doc/vocabularium/transportnetwerk/pieter/templates --rootTemplate transportnetwerk-voc.j2 --silent false --language nl  

#||# oslo-generator-html for language en  

#||# -------------------------------------  

#||# command: oslo-generator-html --input /tmp/workspace/report4/html/doc/vocabularium/transportnetwerk/pieter/html/int_transportnetwerk_en.json --output /tmp/workspace/target/doc/vocabularium/transportnetwerk/pieter/index_en.html --stakeholders /tmp/workspace/report4/doc/vocabularium/transportnetwerk/pieter/stakeholders.json --metadata /tmp/workspace/report4/doc/vocabularium/transportnetwerk/pieter/html/meta_transportnetwerk_en.json --specificationType Vocabulary --specificationName --templates /tmp/workspace/report4/doc/vocabularium/transportnetwerk/pieter/templates --rootTemplate transportnetwerk-voc_en.j2 --silent false --language en  

Error: template not found: /tmp/workspace/report4/doc/vocabularium/transportnetwerk/pieter/templates/transportnetwerk-voc_en.j2

    at createTemplate (/usr/local/lib/oslo/node_modules/nunjucks/src/environment.js:234:15)

    at next (/usr/local/lib/oslo/node_modules/nunjucks/src/lib.js:260:7)

    at handle (/usr/local/lib/oslo/node_modules/nunjucks/src/environment.js:267:11)

    at /usr/local/lib/oslo/node_modules/nunjucks/src/environment.js:276:9

    at next (/usr/local/lib/oslo/node_modules/nunjucks/src/lib.js:258:7)

    at Object.asyncIter (/usr/local/lib/oslo/node_modules/nunjucks/src/lib.js:263:3)

    at Environment.getTemplate (/usr/local/lib/oslo/node_modules/nunjucks/src/environment.js:259:9)

    at Environment.render (/usr/local/lib/oslo/node_modules/nunjucks/src/environment.js:295:10)

    at Object.render (/usr/local/lib/oslo/node_modules/nunjucks/index.js:72:14)

    at HtmlGenerationService.run (/usr/local/lib/oslo/packages/oslo-generator-html/lib/HtmlGenerationService.js:118:25)

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/vocabularium/transportnetwerk/pieter/all-transportnetwerk.jsonld -o /tmp/reportlines  


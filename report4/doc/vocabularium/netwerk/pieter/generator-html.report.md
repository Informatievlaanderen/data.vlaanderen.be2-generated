#||# oslo-generator-html for language nl  

#||# -------------------------------------  

#||# command: oslo-generator-html --input /tmp/workspace/report4/html/doc/vocabularium/netwerk/pieter/html/int_netwerk_nl.json --output /tmp/workspace/target/doc/vocabularium/netwerk/pieter/index_nl.html --stakeholders /tmp/workspace/report4/doc/vocabularium/netwerk/pieter/stakeholders.json --metadata /tmp/workspace/report4/doc/vocabularium/netwerk/pieter/html/meta_netwerk_nl.json --specificationType Vocabulary --specificationName --templates /tmp/workspace/report4/doc/vocabularium/netwerk/pieter/templates --rootTemplate netwerk-voc.j2 --silent false --language nl  

#||# oslo-generator-html for language en  

#||# -------------------------------------  

#||# command: oslo-generator-html --input /tmp/workspace/report4/html/doc/vocabularium/netwerk/pieter/html/int_netwerk_en.json --output /tmp/workspace/target/doc/vocabularium/netwerk/pieter/index_en.html --stakeholders /tmp/workspace/report4/doc/vocabularium/netwerk/pieter/stakeholders.json --metadata /tmp/workspace/report4/doc/vocabularium/netwerk/pieter/html/meta_netwerk_en.json --specificationType Vocabulary --specificationName --templates /tmp/workspace/report4/doc/vocabularium/netwerk/pieter/templates --rootTemplate netwerk-voc_en.j2 --silent false --language en  

Error: template not found: /tmp/workspace/report4/doc/vocabularium/netwerk/pieter/templates/netwerk-voc_en.j2

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

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/vocabularium/netwerk/pieter/all-netwerk.jsonld -o /tmp/reportlines  


#||# oslo-generator-html for language nl  

#||# -------------------------------------  

#||# command: oslo-generator-html --input /tmp/workspace/report4/html/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/kristof-t/html/int_zaalreservatie_nl.json --output /tmp/workspace/target/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/kristof-t/index_nl.html --stakeholders /tmp/workspace/report4/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/kristof-t/stakeholders.json --metadata /tmp/workspace/report4/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/kristof-t/html/meta_zaalreservatie_nl.json --specificationType ApplicationProfile --specificationName --templates /tmp/workspace/report4/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/kristof-t/templates --rootTemplate zaalreservatie-ap.j2 --silent false --language nl  

#||# oslo-generator-html for language en  

#||# -------------------------------------  

#||# command: oslo-generator-html --input /tmp/workspace/report4/html/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/kristof-t/html/int_zaalreservatie_en.json --output /tmp/workspace/target/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/kristof-t/index_en.html --stakeholders /tmp/workspace/report4/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/kristof-t/stakeholders.json --metadata /tmp/workspace/report4/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/kristof-t/html/meta_zaalreservatie_en.json --specificationType ApplicationProfile --specificationName --templates /tmp/workspace/report4/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/kristof-t/templates --rootTemplate zaalreservatie-ap_en.j2 --silent false --language en  

Error: template not found: /tmp/workspace/report4/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/kristof-t/templates/zaalreservatie-ap_en.j2

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

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/zaalreservatie/kandidaatstandaard/kristof-t/all-zaalreservatie.jsonld -o /tmp/reportlines  


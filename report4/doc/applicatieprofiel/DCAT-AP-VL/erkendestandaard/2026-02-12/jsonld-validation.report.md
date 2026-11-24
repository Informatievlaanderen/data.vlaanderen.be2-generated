#||# oslo-jsonld-validator   

#||# -------------------------------------  

#||# command: oslo-jsonld-validator --input /tmp/workspace/report4/doc/applicatieprofiel/DCAT-AP-VL/erkendestandaard/2026-02-12/all-DCAT-AP-VL.jsonld --whitelist https://raw.githubusercontent.com/Informatievlaanderen/OSLO-UML-Transformer/refs/heads/configuration/whitelist.json --specificationType ApplicationProfile --publicationEnvironment data.vlaanderen.be --language nl  

2026-11-24T07:48:29.248Z info: [JsonLdValidationService]: Loaded 75 URI prefixes into whitelist

2026-11-24T07:48:29.710Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://data.vlaanderen.be/ns/generiek#gestructureerdeIdentificator for subject: [urn:oslo-toolchain:867259d266b6394d1a67918dafc939546fdf50247ba9dce3c56ce18f49cb4223](all-DCAT-AP-VL.jsonld#L4743)

2026-11-24T07:48:29.710Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://schema.org/ContactPoint for subject: [urn:oslo-toolchain:013904af3189e8feae623d00dc7bb9c3fc4235f0964568a9c92ff9e4cc851bb2](all-DCAT-AP-VL.jsonld#L9302)

2026-11-24T07:48:29.710Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://data.vlaanderen.be/ns/generiek#GestructureerdeIdentificator for subject: [urn:oslo-toolchain:92014220bf23084ddfabd854551ef4a43996ce963c6a66006390ce84fa7f8830](all-DCAT-AP-VL.jsonld#L9508)

2026-11-24T07:48:29.712Z warn: [JsonLdValidationService]: Found abbreviation 'e.g' in sentence 'Een beschrijving van de diensten die beschikbaar zijn via de endpoints, met inbegrip van e.g. hun operaties, parameters.' for subject: [urn:oslo-toolchain:dbeda3bf59c9bbf520a27208169ba690c422e7e87f68d22ed99b893553deeb38](all-DCAT-AP-VL.jsonld#L3768), replace with 'bijvoorbeeld'

2026-11-24T07:48:29.713Z warn: [JsonLdValidationService]: Found abbreviation 'b.v' in sentence 'Een webpagina die ofwel toelaat om contact op te nemen (via b.v. een webformulier) of die informatie bevat hoe men contact kan opnemen.' for subject: [urn:oslo-toolchain:3bdb386d405d1e4523bac74605ce830c19831f76e7b677f0b51283efb2706df0](all-DCAT-AP-VL.jsonld#L6305), replace with 'bijvoorbeeld'

2026-11-24T07:48:29.713Z warn: [JsonLdValidationService]: Found sentence without a '.': 'De agent die de eigendomsrechten heeft?' for subject: [urn:oslo-toolchain:cfe7a41a4358db3dd619459fb01958adfead9248e3f4ccb185717e4eb7406a53](all-DCAT-AP-VL.jsonld#L8764)

2026-11-24T07:48:29.713Z warn: [JsonLdValidationService]: Found sentence without a '.': 'De catalogus resource waarin de relatie eindigt' for subject: [urn:oslo-toolchain:0512a862d47557595179f9f7164576c83752a10d3eac0ceac42ada2fe7aebccc](all-DCAT-AP-VL.jsonld#L9104)

2026-11-24T07:48:29.713Z warn: [JsonLdValidationService]: Found abbreviation 'vd' in sentence 'Naam vd agent die de identificator heeft toegekend.' for subject: [urn:oslo-toolchain:8d1479f576cca4202e6c6317bd8e701f7596050856c47841dbd408643f728136](all-DCAT-AP-VL.jsonld#L1755), replace with 'van de'

2026-11-24T07:48:29.713Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Een verwijzing naar de statuspagina van de dataservice' for subject: [urn:oslo-toolchain:ae66e5983f426984a3a7ad3d50875fc6b27c0d33460656868d464b43d1c8afdd](all-DCAT-AP-VL.jsonld#L4326)

2026-11-24T07:48:29.713Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Identificator vh object opgesplitst in zijn onderdelen.' for subject: [urn:oslo-toolchain:867259d266b6394d1a67918dafc939546fdf50247ba9dce3c56ce18f49cb4223](all-DCAT-AP-VL.jsonld#L4743), replace with 'van het'

2026-11-24T07:48:29.714Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'In DCAT-AP VL 3.0 worden datasetseries opgevat in hun zuivere betekenis: een verzameling van datasets die dezelfde specificaties delen, waarbij de enige variërende eigenschap typisch ruimte of tijd/versie is. Dit sluit nauw aan bij ISO 19115-1 en INSPIRE, waar een datasetserie wordt gedefinieerd als een collectie datasets met een gemeenschappelijke productspecificatie. Deze zuivere vorm wordt in DCAT-AP VL 3.0 volledig ondersteund. 

<br/>

Daarnaast bestaan in de praktijk verschillende tussenvormen - zoals verzamelingen van datasets over eenzelfde thema, verzamelingen van datasets, series en services, of collecties gebaseerd op bron- of eigenschapsgelijkheid. Deze structuren hebben een grotere “vrijheidsgraad” (variatie in versie, gebied, specificaties, brontypes of eigenschappen) en voldoen daardoor niet aan de formele definitie van datasetseries. Deze tussenvormen worden daarom niet als datasetseries ondersteund, maar wel vindbaar gemaakt via passende DCAT-structuren (bv. thema-gebaseerde groepering of catalogusstructuren). 

<br/>

Voor complexe of expliciet gestructureerde groeperingen is de correcte representatie een (sub)catalogus, waarbij de verbindende eigenschap expliciet door de catalogus zelf wordt bepaald. Subcatalogi worden wél ondersteund in DCAT-AP VL 3.0.' for subject: [urn:oslo-toolchain:2c30d56b28583290f49888b2aef7773937e6a8420fc11d62189a3c9a9f67eb93](all-DCAT-AP-VL.jsonld#L673), replace with 'bijvoorbeeld'

2026-11-24T07:48:29.715Z warn: [JsonLdValidationService]: Found abbreviation 'e.g' in sentence 'Deze eigenschap capteert de technische specificatie waaraan de service voldoet, e.g. WFS, SPARQL, SOAP…' for subject: [urn:oslo-toolchain:7a2ce0567dc27d9a81e12201de0df4887f43df22d2c350f5ab155f6bbe21015e](all-DCAT-AP-VL.jsonld#L5245), replace with 'bijvoorbeeld'

2026-11-24T07:48:29.715Z warn: [JsonLdValidationService]: Found abbreviation 'E.g' in sentence 'E.g. de webpagina van de servicedesk van de organisatie.' for subject: [urn:oslo-toolchain:3bdb386d405d1e4523bac74605ce830c19831f76e7b677f0b51283efb2706df0](all-DCAT-AP-VL.jsonld#L6305), replace with 'bijvoorbeeld'

2026-11-24T07:48:29.715Z warn: [JsonLdValidationService]: Found abbreviation 'b.v' in sentence 'Wanneer geografische dekking een dimensie is in de datasetserie, moet de geografische dekking van elke dataset in de collectie deel uitmaken van de geografisch dekking. Er wordt een waarde met een open einde aanbevolen, b.v. EU of een alomvattende bouding box dat de verwachte waarden bevat.' for subject: [urn:oslo-toolchain:67744513a732fa79dc49006ef2669db7a55fd7d9f9ab3c8623c4216733a7bbc0](all-DCAT-AP-VL.jsonld#L6931), replace with 'bijvoorbeeld'

2026-11-24T07:48:29.716Z warn: [JsonLdValidationService]: Labels must only contain alphabetical characters: 'toegekend door (String)' for subject: [urn:oslo-toolchain:8d1479f576cca4202e6c6317bd8e701f7596050856c47841dbd408643f728136](all-DCAT-AP-VL.jsonld#L1755)

2026-11-24T07:48:29.717Z warn: [JsonLdValidationService]: Labels must only contain alphabetical characters: 'e-mail' for subject: [urn:oslo-toolchain:92e4cc053adfaa9e24ad0a347b6179a0e2b002a51ba70453e4ff3d792c7c432f](all-DCAT-AP-VL.jsonld#L4851)

2026-11-24T07:48:29.721Z info: [JsonLdValidationService]: Validation found 3 non-whitelisted assigned URIs

2026-11-24T07:48:29.721Z info: [JsonLdValidationService]: Validation found 11 sentences with spelling mistakes or abbreviations.

2026-11-24T07:48:29.721Z info: [JsonLdValidationService]: Validation found 2 labels with spelling mistakes or abbreviations.

2026-11-24T07:48:29.721Z info: [JsonLdValidationService]: Validation successful! All base URIs seem to be valid.

2026-11-24T07:48:29.721Z info: [JsonLdValidationService]: Validation successful! All referenced classes and attributes seem to be included.

#||# oslo-jsonld-validator   

#||# -------------------------------------  

#||# command: oslo-jsonld-validator --input /tmp/workspace/report4/doc/applicatieprofiel/DCAT-AP-VL/erkendestandaard/2026-02-12/all-DCAT-AP-VL.jsonld --whitelist https://raw.githubusercontent.com/Informatievlaanderen/OSLO-UML-Transformer/refs/heads/configuration/whitelist.json --specificationType ApplicationProfile --publicationEnvironment data.vlaanderen.be --language nl  

2026-11-24T07:48:30.713Z info: [JsonLdValidationService]: Loaded 75 URI prefixes into whitelist

2026-11-24T07:48:31.215Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://data.vlaanderen.be/ns/generiek#gestructureerdeIdentificator for subject: [urn:oslo-toolchain:867259d266b6394d1a67918dafc939546fdf50247ba9dce3c56ce18f49cb4223](all-DCAT-AP-VL.jsonld#L4743)

2026-11-24T07:48:31.215Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://schema.org/ContactPoint for subject: [urn:oslo-toolchain:013904af3189e8feae623d00dc7bb9c3fc4235f0964568a9c92ff9e4cc851bb2](all-DCAT-AP-VL.jsonld#L9302)

2026-11-24T07:48:31.215Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://data.vlaanderen.be/ns/generiek#GestructureerdeIdentificator for subject: [urn:oslo-toolchain:92014220bf23084ddfabd854551ef4a43996ce963c6a66006390ce84fa7f8830](all-DCAT-AP-VL.jsonld#L9508)

2026-11-24T07:48:31.217Z warn: [JsonLdValidationService]: Found abbreviation 'e.g' in sentence 'Een beschrijving van de diensten die beschikbaar zijn via de endpoints, met inbegrip van e.g. hun operaties, parameters.' for subject: [urn:oslo-toolchain:dbeda3bf59c9bbf520a27208169ba690c422e7e87f68d22ed99b893553deeb38](all-DCAT-AP-VL.jsonld#L3768), replace with 'bijvoorbeeld'

2026-11-24T07:48:31.218Z warn: [JsonLdValidationService]: Found abbreviation 'b.v' in sentence 'Een webpagina die ofwel toelaat om contact op te nemen (via b.v. een webformulier) of die informatie bevat hoe men contact kan opnemen.' for subject: [urn:oslo-toolchain:3bdb386d405d1e4523bac74605ce830c19831f76e7b677f0b51283efb2706df0](all-DCAT-AP-VL.jsonld#L6305), replace with 'bijvoorbeeld'

2026-11-24T07:48:31.218Z warn: [JsonLdValidationService]: Found sentence without a '.': 'De agent die de eigendomsrechten heeft?' for subject: [urn:oslo-toolchain:cfe7a41a4358db3dd619459fb01958adfead9248e3f4ccb185717e4eb7406a53](all-DCAT-AP-VL.jsonld#L8764)

2026-11-24T07:48:31.218Z warn: [JsonLdValidationService]: Found sentence without a '.': 'De catalogus resource waarin de relatie eindigt' for subject: [urn:oslo-toolchain:0512a862d47557595179f9f7164576c83752a10d3eac0ceac42ada2fe7aebccc](all-DCAT-AP-VL.jsonld#L9104)

2026-11-24T07:48:31.218Z warn: [JsonLdValidationService]: Found abbreviation 'vd' in sentence 'Naam vd agent die de identificator heeft toegekend.' for subject: [urn:oslo-toolchain:8d1479f576cca4202e6c6317bd8e701f7596050856c47841dbd408643f728136](all-DCAT-AP-VL.jsonld#L1755), replace with 'van de'

2026-11-24T07:48:31.218Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Een verwijzing naar de statuspagina van de dataservice' for subject: [urn:oslo-toolchain:ae66e5983f426984a3a7ad3d50875fc6b27c0d33460656868d464b43d1c8afdd](all-DCAT-AP-VL.jsonld#L4326)

2026-11-24T07:48:31.219Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Identificator vh object opgesplitst in zijn onderdelen.' for subject: [urn:oslo-toolchain:867259d266b6394d1a67918dafc939546fdf50247ba9dce3c56ce18f49cb4223](all-DCAT-AP-VL.jsonld#L4743), replace with 'van het'

2026-11-24T07:48:31.219Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'In DCAT-AP VL 3.0 worden datasetseries opgevat in hun zuivere betekenis: een verzameling van datasets die dezelfde specificaties delen, waarbij de enige variërende eigenschap typisch ruimte of tijd/versie is. Dit sluit nauw aan bij ISO 19115-1 en INSPIRE, waar een datasetserie wordt gedefinieerd als een collectie datasets met een gemeenschappelijke productspecificatie. Deze zuivere vorm wordt in DCAT-AP VL 3.0 volledig ondersteund. 

<br/>

Daarnaast bestaan in de praktijk verschillende tussenvormen - zoals verzamelingen van datasets over eenzelfde thema, verzamelingen van datasets, series en services, of collecties gebaseerd op bron- of eigenschapsgelijkheid. Deze structuren hebben een grotere “vrijheidsgraad” (variatie in versie, gebied, specificaties, brontypes of eigenschappen) en voldoen daardoor niet aan de formele definitie van datasetseries. Deze tussenvormen worden daarom niet als datasetseries ondersteund, maar wel vindbaar gemaakt via passende DCAT-structuren (bv. thema-gebaseerde groepering of catalogusstructuren). 

<br/>

Voor complexe of expliciet gestructureerde groeperingen is de correcte representatie een (sub)catalogus, waarbij de verbindende eigenschap expliciet door de catalogus zelf wordt bepaald. Subcatalogi worden wél ondersteund in DCAT-AP VL 3.0.' for subject: [urn:oslo-toolchain:2c30d56b28583290f49888b2aef7773937e6a8420fc11d62189a3c9a9f67eb93](all-DCAT-AP-VL.jsonld#L673), replace with 'bijvoorbeeld'

2026-11-24T07:48:31.220Z warn: [JsonLdValidationService]: Found abbreviation 'e.g' in sentence 'Deze eigenschap capteert de technische specificatie waaraan de service voldoet, e.g. WFS, SPARQL, SOAP…' for subject: [urn:oslo-toolchain:7a2ce0567dc27d9a81e12201de0df4887f43df22d2c350f5ab155f6bbe21015e](all-DCAT-AP-VL.jsonld#L5245), replace with 'bijvoorbeeld'

2026-11-24T07:48:31.220Z warn: [JsonLdValidationService]: Found abbreviation 'E.g' in sentence 'E.g. de webpagina van de servicedesk van de organisatie.' for subject: [urn:oslo-toolchain:3bdb386d405d1e4523bac74605ce830c19831f76e7b677f0b51283efb2706df0](all-DCAT-AP-VL.jsonld#L6305), replace with 'bijvoorbeeld'

2026-11-24T07:48:31.220Z warn: [JsonLdValidationService]: Found abbreviation 'b.v' in sentence 'Wanneer geografische dekking een dimensie is in de datasetserie, moet de geografische dekking van elke dataset in de collectie deel uitmaken van de geografisch dekking. Er wordt een waarde met een open einde aanbevolen, b.v. EU of een alomvattende bouding box dat de verwachte waarden bevat.' for subject: [urn:oslo-toolchain:67744513a732fa79dc49006ef2669db7a55fd7d9f9ab3c8623c4216733a7bbc0](all-DCAT-AP-VL.jsonld#L6931), replace with 'bijvoorbeeld'

2026-11-24T07:48:31.221Z warn: [JsonLdValidationService]: Labels must only contain alphabetical characters: 'toegekend door (String)' for subject: [urn:oslo-toolchain:8d1479f576cca4202e6c6317bd8e701f7596050856c47841dbd408643f728136](all-DCAT-AP-VL.jsonld#L1755)

2026-11-24T07:48:31.222Z warn: [JsonLdValidationService]: Labels must only contain alphabetical characters: 'e-mail' for subject: [urn:oslo-toolchain:92e4cc053adfaa9e24ad0a347b6179a0e2b002a51ba70453e4ff3d792c7c432f](all-DCAT-AP-VL.jsonld#L4851)

2026-11-24T07:48:31.229Z info: [JsonLdValidationService]: Validation found 3 non-whitelisted assigned URIs

2026-11-24T07:48:31.229Z info: [JsonLdValidationService]: Validation found 11 sentences with spelling mistakes or abbreviations.

2026-11-24T07:48:31.229Z info: [JsonLdValidationService]: Validation found 2 labels with spelling mistakes or abbreviations.

2026-11-24T07:48:31.229Z info: [JsonLdValidationService]: Validation successful! All base URIs seem to be valid.

2026-11-24T07:48:31.229Z info: [JsonLdValidationService]: Validation successful! All referenced classes and attributes seem to be included.

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/DCAT-AP-VL/erkendestandaard/2026-02-12/all-DCAT-AP-VL.jsonld -o /tmp/reportlines  


#||# oslo-jsonld-validator   

#||# -------------------------------------  

#||# command: oslo-jsonld-validator --input /tmp/workspace/report4/doc/applicatieprofiel/mobiliteit/passenger-transport-hubs/pieter/all-passenger-transport-hubs.jsonld --whitelist https://raw.githubusercontent.com/Informatievlaanderen/OSLO-UML-Transformer/refs/heads/configuration/whitelist.json --specificationType ApplicationProfile --publicationEnvironment data.vlaanderen.be --language en  

2026-10-26T10:25:17.830Z info: [JsonLdValidationService]: Loaded 56 URI prefixes into whitelist

2026-10-26T10:25:18.788Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://data.vlaanderen.be/doc/applicatieprofiel/infrastructuurelementen/#Infozuil for subject: [urn:oslo-toolchain:856502f5df85c33f509757877ddd777853c59b4a6eb70ec434bfb96d9d16b348](all-passenger-transport-hubs.jsonld#L632)

2026-10-26T10:25:18.789Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://wegenenverkeer.data.vlaanderen.be/ns/abstracten#Hoppinzuil.zuilnaam for subject: [urn:oslo-toolchain:a72674fee0d6abc74e0f2a00203ca4180b2ce46772d506edca44ade0d1dd5d75](all-passenger-transport-hubs.jsonld#L5112)

2026-10-26T10:25:18.789Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://wegenenverkeer.data.vlaanderen.be/ns/abstracten#Hoppinzuil.zuilnummer for subject: [urn:oslo-toolchain:b7543bf8834bc7177670b681794d92b8b9ef56de49085ce503abba6c322288e8](all-passenger-transport-hubs.jsonld#L5178)

2026-10-26T10:25:18.789Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://wegenenverkeer.data.vlaanderen.be/ns/abstracten#Hoppinzuil.weergegevenVervoersmodiOpKaart for subject: [urn:oslo-toolchain:a548a02f67ba28acb1d70a9aa9bd47fc51f8236ca74ab25f4df12f65f7e3e8fc](all-passenger-transport-hubs.jsonld#L9088)

2026-10-26T10:25:18.789Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://todo.com/realisedOn for subject: [urn:oslo-toolchain:c080b0370aab1dfe0ccf626f4721534faeecb5b7d45c3a16a3ad189e9c5d5a2a](all-passenger-transport-hubs.jsonld#L13882)

2026-10-26T10:25:18.789Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://todo.com/parkingSpace for subject: [urn:oslo-toolchain:71f6bfa8b02f6b9eec98eec931815f7890abbdf64b46022965d7b2b80dec9a6d](all-passenger-transport-hubs.jsonld#L15070)

2026-10-26T10:25:18.789Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://todo.com/service for subject: [urn:oslo-toolchain:8f80e2833d5df9da1d981519a63cc98c897cd8dd5e3e307bde7b1a1e9a700839](all-passenger-transport-hubs.jsonld#L15182)

2026-10-26T10:25:18.789Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://todo.com/service for subject: [urn:oslo-toolchain:e1f13575336258812827a392a89b6f0aff35249e7ac570133c7aaf4feb083760](all-passenger-transport-hubs.jsonld#L16628)

2026-10-26T10:25:18.789Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://todo.com/transportHub for subject: [urn:oslo-toolchain:60f2d137a7dd37bda44bfb88573dcde967418944f75960d82d830f297435b8a6](all-passenger-transport-hubs.jsonld#L15446)

2026-10-26T10:25:18.790Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://todo.com/transportObject for subject: [urn:oslo-toolchain:0f7c29e0b590bc1c0aa33875e607306a30c9492ed9e87528a14113c378adb956](all-passenger-transport-hubs.jsonld#L15776)

2026-10-26T10:25:18.790Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://todo.com/realisedWith for subject: [urn:oslo-toolchain:75855f3d2c6f92d28ecff66c76fe3e6fb6846ae8fe877652f9f349a9d93e6289](all-passenger-transport-hubs.jsonld#L15842)

2026-10-26T10:25:18.790Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: http://todo.com/Site for subject: [urn:oslo-toolchain:753131a8b1fa57ddcc2d5cccf3583ccf17b43869aa2949958927e7fd038e056e](all-passenger-transport-hubs.jsonld#L17893)

2026-10-26T10:25:18.798Z warn: [JsonLdValidationService]: Found a TODO or FIXME in sentence: 'TODO' for subject: [urn:oslo-toolchain:753131a8b1fa57ddcc2d5cccf3583ccf17b43869aa2949958927e7fd038e056e](all-passenger-transport-hubs.jsonld#L17893)

2026-10-26T10:25:18.809Z error: [JsonLdValidationService]: Found missing class or attribute (RouteNode (source)): [urn:oslo-toolchain:c96395beb4807dd9cfe974830d1953fe418be77acab9cfd37d6d8c2c9dc6d4af](all-passenger-transport-hubs.jsonld#L14364) in Application Profile

2026-10-26T10:25:18.809Z error: [JsonLdValidationService]: Found missing class or attribute (RouteNode (target)): [urn:oslo-toolchain:a96e5f8f8b7b2555541e057d68d265587f6b43181a55369ba6fa69ca1e5ce5b8](all-passenger-transport-hubs.jsonld#L14390) in Application Profile

2026-10-26T10:25:18.809Z error: [JsonLdValidationService]: Found missing class or attribute (parkingSpace): [urn:oslo-toolchain:71f6bfa8b02f6b9eec98eec931815f7890abbdf64b46022965d7b2b80dec9a6d](all-passenger-transport-hubs.jsonld#L15070) in Application Profile

2026-10-26T10:25:18.810Z error: [JsonLdValidationService]: Found missing class or attribute (Pseudonym): [urn:oslo-toolchain:32ebaf3430bef7e75ceb74b9aafaf6706bdc390059facf2c660dc24efb33e246](all-passenger-transport-hubs.jsonld#L17953) in Application Profile

2026-10-26T10:25:18.810Z error: [JsonLdValidationService]: Found missing class or attribute (Toegankelijkheidstype): [urn:oslo-toolchain:aab6192a70c2a75e72a8285134ed520e1797fd0574de5b75aca3e51e03c52081](all-passenger-transport-hubs.jsonld#L17988) in Application Profile

2026-10-26T10:25:18.810Z info: [JsonLdValidationService]: Validation found 12 non-whitelisted assigned URIs

2026-10-26T10:25:18.810Z info: [JsonLdValidationService]: Validation found 1 sentences with spelling mistakes or abbreviations.

2026-10-26T10:25:18.810Z info: [JsonLdValidationService]: Validation successful! All labels seem to be valid, no spelling mistakes or abbreviations found.

2026-10-26T10:25:18.810Z info: [JsonLdValidationService]: Validation successful! All base URIs seem to be valid.

2026-10-26T10:25:18.810Z info: [JsonLdValidationService]: Validation found 5 missing referenced classes or attributes.

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/mobiliteit/passenger-transport-hubs/pieter/all-passenger-transport-hubs.jsonld -o /tmp/reportlines  


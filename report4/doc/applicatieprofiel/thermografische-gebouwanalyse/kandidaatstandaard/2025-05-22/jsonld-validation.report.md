#||# oslo-jsonld-validator   

#||# -------------------------------------  

#||# command: oslo-jsonld-validator --input /tmp/workspace/report4/doc/applicatieprofiel/thermografische-gebouwanalyse/kandidaatstandaard/2025-05-22/all-thermografische-gebouwanalyse.jsonld --whitelist https://raw.githubusercontent.com/Informatievlaanderen/OSLO-UML-Transformer/refs/heads/configuration/whitelist.json --specificationType ApplicationProfile --publicationEnvironment data.vlaanderen.be --language nl  

2026-10-08T19:29:00.602Z info: [JsonLdValidationService]: Loaded 56 URI prefixes into whitelist

2026-10-08T19:29:00.830Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://www.w3.org/ns/sosa/Sensor for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194)

2026-10-08T19:29:00.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://www.w3.org/ns/sosa/Platform for subject: [urn:oslo-toolchain:23a58ad8b235a857a57704dbcc3c0cd5c747cb2cd22676d275df8932f7342f91](all-thermografische-gebouwanalyse.jsonld#L7852)

2026-10-08T19:29:00.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://www.w3.org/ns/sosa/Platform for subject: [urn:oslo-toolchain:4147b673ade81ea458b13e54e597c07bbc614dd4cf8fedc06f72c69bafdc25ba](all-thermografische-gebouwanalyse.jsonld#L7941)

2026-10-08T19:29:00.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://www.w3.org/ns/sosa/Platform for subject: [urn:oslo-toolchain:2118013347bed818023bde628fb75fa16625423a5ebe2bbda5d96028b950a19d](all-thermografische-gebouwanalyse.jsonld#L645)

2026-10-08T19:29:00.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://qudt.org/schema/qudt/Unit for subject: [urn:oslo-toolchain:481adc509dbc6e79f7b438bba06bb8cdd47e6ba4498205af5dad72ea75242df8](all-thermografische-gebouwanalyse.jsonld#L1716)

2026-10-08T19:29:00.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://qudt.org/schema/qudt/value for subject: [urn:oslo-toolchain:29cc3e1a71eb3ab20c073b6685187a06633c3d3c619249eb9ecceb1741fd1696](all-thermografische-gebouwanalyse.jsonld#L3535)

2026-10-08T19:29:00.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://dbpedia.org/ontology/influencedBy for subject: [urn:oslo-toolchain:a603925495c15a3c3354f7723e65a8a0c91513af02e261c4811458579fee6d87](all-thermografische-gebouwanalyse.jsonld#L4091)

2026-10-08T19:29:00.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://qudt.org/schema/qudt/hasUnit for subject: [urn:oslo-toolchain:ad8ddd7aec0b15c51570083cf5dd46bd29b325443d23f5c20b8cb73f04c21fb7](all-thermografische-gebouwanalyse.jsonld#L6159)

2026-10-08T19:29:00.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://www.w3.org/ns/sosa/hosts for subject: [urn:oslo-toolchain:ccb5981ce5dced486c6f2c2c725f307a756bd3baf7de00e673bffab585bc8250](all-thermografische-gebouwanalyse.jsonld#L6859)

2026-10-08T19:29:00.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://qudt.org/schema/qudt/QuantityValue for subject: [urn:oslo-toolchain:25161675a715b914d0c25907081fb9b998a12c8886c2b563ec7e88a6ac054eb7](all-thermografische-gebouwanalyse.jsonld#L7721)

2026-10-08T19:29:00.833Z warn: [JsonLdValidationService]: Found abbreviation 'incl' in sentence 'Toestel of Agent (incl Personen of software) waarmee Observaties gemaakt worden.' for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194), replace with 'inclusief'

2026-10-08T19:29:00.834Z warn: [JsonLdValidationService]: Found abbreviation 'dmv' in sentence 'Reeks van stilstaande beelden die snel achter elkaar worden afgespeeld om de illusie van beweging te creëren, vastgelegd dmv een videocamera of bekomen door animatie.' for subject: [[urn:oslo-toolchain:4b3c53866efe16fefd4e6e8a25a568e53340d55f1be93e1422231d1eedc54f34](all-thermografische-gebouwanalyse.jsonld#L7991)](all-thermografische-gebouwanalyse.jsonld#L1117), replace with 'door middel van'

2026-10-08T19:29:00.834Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Capaciteit ve Systeem.' for subject: [urn:oslo-toolchain:50391fddb04a006afc5abbff149112f9eed78ef95bd8e67b98f57f99428d5292](all-thermografische-gebouwanalyse.jsonld#L1382), replace with 'van een'

2026-10-08T19:29:00.834Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Capaciteiten ve Systeem.' for subject: [urn:oslo-toolchain:199891c289cfd023c5bc0e399b8e325967f0f232415c3b5a3a4dc9f190b535d2](all-thermografische-gebouwanalyse.jsonld#L1430), replace with 'van een'

2026-10-08T19:29:00.834Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Levensduur ve Systeem.' for subject: [urn:oslo-toolchain:fda15210d99a1b7d03286cdde99e19652036ef1dbfa485549ac5b9728a1ad583](all-thermografische-gebouwanalyse.jsonld#L1574), replace with 'van een'

2026-10-08T19:29:00.834Z warn: [JsonLdValidationService]: Found abbreviation 'ttz' in sentence 'Immaterieel object dat informatie omvat, ttz gegevens of data waaraan op één of andere manier betekenis is gegeven. Een Informatieobject gaat ergens over (het is propositioneel) en brengt dat over dmv symbolen (karakters, tekens etc.) of aggregaties daarvan.' for subject: [urn:oslo-toolchain:f0249a8683cc17b376b4c2965640c06ecc88fb4bdc6db243e30638ea2b3e6fe4](all-thermografische-gebouwanalyse.jsonld#L1763), replace with 'het is te zeggen'

2026-10-08T19:29:00.834Z warn: [JsonLdValidationService]: Found abbreviation 'dmv' in sentence 'Immaterieel object dat informatie omvat, ttz gegevens of data waaraan op één of andere manier betekenis is gegeven. Een Informatieobject gaat ergens over (het is propositioneel) en brengt dat over dmv symbolen (karakters, tekens etc.) of aggregaties daarvan.' for subject: [urn:oslo-toolchain:f0249a8683cc17b376b4c2965640c06ecc88fb4bdc6db243e30638ea2b3e6fe4](all-thermografische-gebouwanalyse.jsonld#L1763), replace with 'door middel van'

2026-10-08T19:29:00.834Z warn: [JsonLdValidationService]: Found abbreviation 'dmv' in sentence 'Positie in de tijd uitgedrukt dmv xsd:dateTime.' for subject: [urn:oslo-toolchain:a398b95cef8dd002613d6ce0e52a16214c004460c7a39f561a1b940b4ffc1592](all-thermografische-gebouwanalyse.jsonld#L1967), replace with 'door middel van'

2026-10-08T19:29:00.834Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Naam vh model vh Toestel.' for subject: [urn:oslo-toolchain:7420a01e01dbb4fb76f2572ff2ebe5cb315132dd80c8706dd60b91581551c0e8](all-thermografische-gebouwanalyse.jsonld#L2067), replace with 'van het'

2026-10-08T19:29:00.834Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Naam van het model' for subject: [urn:oslo-toolchain:eb9c2c41a935014dca30a0bde5fb850d2c47f4a8be246140388ebdc97ebb118b](all-thermografische-gebouwanalyse.jsonld#L2167)

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Straatnaam vh adres.' for subject: [urn:oslo-toolchain:62bc47107094b5011a78797806ed0d963cff62acca7fe332209c10245a514631](all-thermografische-gebouwanalyse.jsonld#L2689), replace with 'van het'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Naam of omschrijving vh het geografisch object dat de adreslocator aanduidt.' for subject: [urn:oslo-toolchain:c615b7a2cf1206b3a51c7cf52129034280f99797461afd9adf44f9d8f0309436](all-thermografische-gebouwanalyse.jsonld#L2931), replace with 'van het'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Naam ve geografisch gebied of plaats die een aantal adresseerbare objecten groepeert om deze te adresseren zonder dat het gebied of de plaats een administratieve eenheid is' for subject: [urn:oslo-toolchain:b47c8d694583794d904c41d2aae1cad8780e3292cc7546ed21ab56e108a7f844](all-thermografische-gebouwanalyse.jsonld#L2987), replace with 'van een'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Gemeentenaam vh adres.' for subject: [urn:oslo-toolchain:2d33c1fd6375253e9654fc4a408ef02f61e6c72f9fcf862c1317cff616f4dbd0](all-thermografische-gebouwanalyse.jsonld#L3105), replace with 'van het'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'De regio vh adres, doorgaans een provincie of deelstaat of gelijkaardig gebied dat typisch meerdere plaatsen omvat.' for subject: [urn:oslo-toolchain:fe1a28e047d181c88fe215f982b704bf0baf20e4a0cf62de69b9bd52b273811a](all-thermografische-gebouwanalyse.jsonld#L3164), replace with 'van het'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Hoogste administratieve eenheid vh adres, doorgaans een land.' for subject: [urn:oslo-toolchain:a8ecca9f7a61f0b807205faebd4f04de1e09088ea830709a7834299003abaa79](all-thermografische-gebouwanalyse.jsonld#L3220), replace with 'van het'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Naam vh type van de waarde.' for subject: [urn:oslo-toolchain:b7096add1860ac1b55bc980d96333c3b18a1f5a00e1b680e2de1fce5e1255472](all-thermografische-gebouwanalyse.jsonld#L3491), replace with 'van het'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Bepaalde hoeveelheid' for subject: [urn:oslo-toolchain:29cc3e1a71eb3ab20c073b6685187a06633c3d3c619249eb9ecceb1741fd1696](all-thermografische-gebouwanalyse.jsonld#L3535)

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Einde ve Temporele Entiteit.' for subject: [urn:oslo-toolchain:b520bc226e344e25deca7cd6bd9458a7588d413d7fbf390518c67802cb16ecef](all-thermografische-gebouwanalyse.jsonld#L4147), replace with 'van een'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Start ve Temporele Entiteit.' for subject: [urn:oslo-toolchain:783f89885bbc75afac686efd099fa544215f6eefa8ba2627a95ea13b80926c77](all-thermografische-gebouwanalyse.jsonld#L4297), replace with 'van een'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Aard vh Systeem.' for subject: [urn:oslo-toolchain:74ad9e0fa03d3285ed5c9e15be925f98e246b279ffbc78e03d74d90b93241bbc](all-thermografische-gebouwanalyse.jsonld#L4447), replace with 'van het'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Capaciteit vh Systeem.' for subject: [urn:oslo-toolchain:b1de2524807d7078cdb4b6a2274127db4dd2ffa767f4e41f6d6b1da54507d8c9](all-thermografische-gebouwanalyse.jsonld#L4497), replace with 'van het'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Werking vh Systeem.' for subject: [urn:oslo-toolchain:583605ad824d939144f7f83e364078cc4854da8e8ddacc3e8b762f8fc6cdef73](all-thermografische-gebouwanalyse.jsonld#L4547), replace with 'van het'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Levensduur vh Systeem.' for subject: [urn:oslo-toolchain:450c3e98d9092cf62a1c5f4e4c0652ae5cbecb1f783a9d2aef14da10c4cb600b](all-thermografische-gebouwanalyse.jsonld#L4597), replace with 'van het'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Aard vh Platform.' for subject: [urn:oslo-toolchain:092cfc640b8c07d1f682396f27cc3ad742422fe9ed628b130162e84edc7fe3ee](all-thermografische-gebouwanalyse.jsonld#L4647), replace with 'van het'

2026-10-08T19:29:00.835Z warn: [JsonLdValidationService]: Found abbreviation 'vd' in sentence 'De fenomeentijd vd Observaties.' for subject: [urn:oslo-toolchain:01ff43a785c669dbee16d3f2751d0ce642918da61c13b45ac71dcde5b31f4ca7](all-thermografische-gebouwanalyse.jsonld#L5459), replace with 'van de'

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found abbreviation 'ttz' in sentence 'Temporele Entiteit waarvan de omvang en duurtijd verschilt van nul, ttz waarvoor de begin- en eindtijd verschillend zijn.' for subject: [urn:oslo-toolchain:8cbf65d213c6a1aa3cfcfc2726b923ce9574e92917de59bde4dc246fc9a0b83f](all-thermografische-gebouwanalyse.jsonld#L7554), replace with 'het is te zeggen'

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Eigenschap die iedereen in een groep heeft' for subject: [urn:oslo-toolchain:ddddd9bbc1f8c8c371220dd2f80302c37a479dfb5cf2589d1ac2bc7baf793d0b](all-thermografische-gebouwanalyse.jsonld#L8110)

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found abbreviation 'incl' in sentence 'Toestel of Agent (incl Personen of software) waarmee Observaties gemaakt worden.' for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194), replace with 'inclusief'

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Domeinobject' for subject: [urn:oslo-toolchain:abb4b0e6ef8d096b8fb5ef18795462129d9a0b583355f36171d55e1dca66f2d8](all-thermografische-gebouwanalyse.jsonld#L1023)

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Capaciteit ve Systeem.' for subject: [urn:oslo-toolchain:50391fddb04a006afc5abbff149112f9eed78ef95bd8e67b98f57f99428d5292](all-thermografische-gebouwanalyse.jsonld#L1382), replace with 'van een'

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Capaciteiten ve Systeem.' for subject: [urn:oslo-toolchain:199891c289cfd023c5bc0e399b8e325967f0f232415c3b5a3a4dc9f190b535d2](all-thermografische-gebouwanalyse.jsonld#L1430), replace with 'van een'

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Levensduur ve Systeem.' for subject: [urn:oslo-toolchain:fda15210d99a1b7d03286cdde99e19652036ef1dbfa485549ac5b9728a1ad583](all-thermografische-gebouwanalyse.jsonld#L1574), replace with 'van een'

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Holistisch en/of theoretisch begrip van een product' for subject: [urn:oslo-toolchain:d9e63fa0343d384dd2af8fa9f78c7fbda41a3ab5daa0792c76697758a23a876d](all-thermografische-gebouwanalyse.jsonld#L1670)

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found abbreviation 'dmv' in sentence 'Positie in de tijd uitgedrukt dmv xsd:dateTime.' for subject: [urn:oslo-toolchain:a398b95cef8dd002613d6ce0e52a16214c004460c7a39f561a1b940b4ffc1592](all-thermografische-gebouwanalyse.jsonld#L1967), replace with 'door middel van'

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Naam vh model vh Toestel.' for subject: [urn:oslo-toolchain:7420a01e01dbb4fb76f2572ff2ebe5cb315132dd80c8706dd60b91581551c0e8](all-thermografische-gebouwanalyse.jsonld#L2067), replace with 'van het'

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Naam van het model' for subject: [urn:oslo-toolchain:eb9c2c41a935014dca30a0bde5fb850d2c47f4a8be246140388ebdc97ebb118b](all-thermografische-gebouwanalyse.jsonld#L2167)

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Straatnaam vh adres.' for subject: [urn:oslo-toolchain:62bc47107094b5011a78797806ed0d963cff62acca7fe332209c10245a514631](all-thermografische-gebouwanalyse.jsonld#L2689), replace with 'van het'

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Naam of omschrijving vh het geografisch object dat de adreslocator aanduidt.' for subject: [urn:oslo-toolchain:c615b7a2cf1206b3a51c7cf52129034280f99797461afd9adf44f9d8f0309436](all-thermografische-gebouwanalyse.jsonld#L2931), replace with 'van het'

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Naam ve geografisch gebied of plaats die een aantal adresseerbare objecten groepeert om deze te adresseren zonder dat het gebied of de plaats een administratieve eenheid is' for subject: [urn:oslo-toolchain:b47c8d694583794d904c41d2aae1cad8780e3292cc7546ed21ab56e108a7f844](all-thermografische-gebouwanalyse.jsonld#L2987), replace with 'van een'

2026-10-08T19:29:00.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Gemeentenaam vh adres.' for subject: [urn:oslo-toolchain:2d33c1fd6375253e9654fc4a408ef02f61e6c72f9fcf862c1317cff616f4dbd0](all-thermografische-gebouwanalyse.jsonld#L3105), replace with 'van het'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'De regio vh adres, doorgaans een provincie of deelstaat of gelijkaardig gebied dat typisch meerdere plaatsen omvat.' for subject: [urn:oslo-toolchain:fe1a28e047d181c88fe215f982b704bf0baf20e4a0cf62de69b9bd52b273811a](all-thermografische-gebouwanalyse.jsonld#L3164), replace with 'van het'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Hoogste Administratieve eenheid vh adres, doorgaans een land.' for subject: [urn:oslo-toolchain:a8ecca9f7a61f0b807205faebd4f04de1e09088ea830709a7834299003abaa79](all-thermografische-gebouwanalyse.jsonld#L3220), replace with 'van het'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Bepaalde hoeveelheid' for subject: [urn:oslo-toolchain:29cc3e1a71eb3ab20c073b6685187a06633c3d3c619249eb9ecceb1741fd1696](all-thermografische-gebouwanalyse.jsonld#L3535)

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Einde ve TemporeleEntiteit.' for subject: [urn:oslo-toolchain:b520bc226e344e25deca7cd6bd9458a7588d413d7fbf390518c67802cb16ecef](all-thermografische-gebouwanalyse.jsonld#L4147), replace with 'van een'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Start ve TemporeleEntiteit.' for subject: [urn:oslo-toolchain:783f89885bbc75afac686efd099fa544215f6eefa8ba2627a95ea13b80926c77](all-thermografische-gebouwanalyse.jsonld#L4297), replace with 'van een'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Aard vh Systeem.' for subject: [urn:oslo-toolchain:74ad9e0fa03d3285ed5c9e15be925f98e246b279ffbc78e03d74d90b93241bbc](all-thermografische-gebouwanalyse.jsonld#L4447), replace with 'van het'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Capaciteit vh Systeem.' for subject: [urn:oslo-toolchain:b1de2524807d7078cdb4b6a2274127db4dd2ffa767f4e41f6d6b1da54507d8c9](all-thermografische-gebouwanalyse.jsonld#L4497), replace with 'van het'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Werking vh Systeem.' for subject: [urn:oslo-toolchain:583605ad824d939144f7f83e364078cc4854da8e8ddacc3e8b762f8fc6cdef73](all-thermografische-gebouwanalyse.jsonld#L4547), replace with 'van het'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Levensduur vh Systeem.' for subject: [urn:oslo-toolchain:450c3e98d9092cf62a1c5f4e4c0652ae5cbecb1f783a9d2aef14da10c4cb600b](all-thermografische-gebouwanalyse.jsonld#L4597), replace with 'van het'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Aard vh Platform.' for subject: [urn:oslo-toolchain:092cfc640b8c07d1f682396f27cc3ad742422fe9ed628b130162e84edc7fe3ee](all-thermografische-gebouwanalyse.jsonld#L4647), replace with 'van het'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'vd' in sentence 'De fenomeentijd vd Observaties.' for subject: [urn:oslo-toolchain:01ff43a785c669dbee16d3f2751d0ce642918da61c13b45ac71dcde5b31f4ca7](all-thermografische-gebouwanalyse.jsonld#L5459), replace with 'van de'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'ttz' in sentence 'TemporeleEntiteit waarvan de omvang en duurtijd verschilt van nul,ttz waarvoor de begin- en eindwaarde verschillend zijn.' for subject: [urn:oslo-toolchain:8cbf65d213c6a1aa3cfcfc2726b923ce9574e92917de59bde4dc246fc9a0b83f](all-thermografische-gebouwanalyse.jsonld#L7554), replace with 'het is te zeggen'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Eigenschap die iedereen in een groep heeft' for subject: [urn:oslo-toolchain:ddddd9bbc1f8c8c371220dd2f80302c37a479dfb5cf2589d1ac2bc7baf793d0b](all-thermografische-gebouwanalyse.jsonld#L8110)

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'ttz' in sentence 'Sensoren genereren een resultaat op basis van een Stimulus, ttz een verandering in de omgeving, of op basis van resultaten van andere Observaties. Ze worden typisch gehost door een Platform. Voorbeelden zijn snelheidsmeters, gyroscopen, barometers, magnetometers gemonteerd op een smart phone. Ook bv het menselijk oog kan beschouwd worden als een Sensor.' for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194), replace with 'het is te zeggen'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Sensoren genereren een resultaat op basis van een Stimulus, ttz een verandering in de omgeving, of op basis van resultaten van andere Observaties. Ze worden typisch gehost door een Platform. Voorbeelden zijn snelheidsmeters, gyroscopen, barometers, magnetometers gemonteerd op een smart phone. Ook bv het menselijk oog kan beschouwd worden als een Sensor.' for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Deze componenten kunnen Systemen op zich zijn. In deze context zijn het Systemen die een Observatieprocedure realiseren (typisch een Sensor) of waarmee een Bemonsteringsprocedure wordt uitgevoerd (bv een Boorinstallatie).' for subject: [urn:oslo-toolchain:f38bd27a6af42cda44c7d1c555a0fba428f20865a9edc7713dd0458de38d10c9](all-thermografische-gebouwanalyse.jsonld#L7902), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.837Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Deze componenten kunnen Systemen op zich zijn. In deze context zijn het Systemen die een Observatieprocedure realiseren (typisch een Sensor) of waarmee een Bemonsteringsprocedure wordt uitgevoerd (bv een Boorinstallatie).' for subject: [urn:oslo-toolchain:39c408dc8d6a746c3a0ea674094d0c7c51911017ea6f079ede5a16f8253b19b3](all-thermografische-gebouwanalyse.jsonld#L561), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'ihkv' in sentence 'Relevant ihkv het Renovatieproject, bvb EPC-waarde, isolatiewaarde vh dak, vastgesteld of beschermd onroerend erfgoed etc' for subject: [urn:oslo-toolchain:4f73baa3053dec5de1f4cf9fce3f075072154858d793b5a8c39c2a04c1f60d1b](all-thermografische-gebouwanalyse.jsonld#L729), replace with 'in het kader van'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'bvb' in sentence 'Relevant ihkv het Renovatieproject, bvb EPC-waarde, isolatiewaarde vh dak, vastgesteld of beschermd onroerend erfgoed etc' for subject: [urn:oslo-toolchain:4f73baa3053dec5de1f4cf9fce3f075072154858d793b5a8c39c2a04c1f60d1b](all-thermografische-gebouwanalyse.jsonld#L729), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Relevant ihkv het Renovatieproject, bvb EPC-waarde, isolatiewaarde vh dak, vastgesteld of beschermd onroerend erfgoed etc' for subject: [urn:oslo-toolchain:4f73baa3053dec5de1f4cf9fce3f075072154858d793b5a8c39c2a04c1f60d1b](all-thermografische-gebouwanalyse.jsonld#L729), replace with 'van het'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv Observaties die op hetzelfde tijdstip plaatsvonden of hetzelfde Object observeren of door dezelfde sensor zijn gemaakt.' for subject: [urn:oslo-toolchain:1446cd31d631b3eb46805a849b7917659f0ef0af67f095b18626f94954f7fad4](all-thermografische-gebouwanalyse.jsonld#L937), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv Meetbereik,Nauwkeurigheid,Resolutie etc.' for subject: [urn:oslo-toolchain:50391fddb04a006afc5abbff149112f9eed78ef95bd8e67b98f57f99428d5292](all-thermografische-gebouwanalyse.jsonld#L1382), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Slaat op zaken als Meetbereik, Nauwkeurigheid, Afwijking, Resolutie, Responstijd, etc. en de eventuele Condities waaronder die specificaties gelden, bv een Nauwkerigheid van 1mm is gegarandeerd voor afstanden onder de 100 meter.' for subject: [urn:oslo-toolchain:199891c289cfd023c5bc0e399b8e325967f0f232415c3b5a3a4dc9f190b535d2](all-thermografische-gebouwanalyse.jsonld#L1430), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Slaat op zaken als onderhoud of de vereiste netspanning en de eventuele bijkomende condities, bv om de 3 weken is onderhoud nodig (door een gespecialiseerde firma) of de spanning op het net voor de voeding vh Systeem moet tussen 110 en 230 Volt liggen (bij normaal verbruik).' for subject: [urn:oslo-toolchain:dc5e939857178933df81554e906638a1b5bfde28fd13b98472d6fc93a532cb63](all-thermografische-gebouwanalyse.jsonld#L1478), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Slaat op zaken als onderhoud of de vereiste netspanning en de eventuele bijkomende condities, bv om de 3 weken is onderhoud nodig (door een gespecialiseerde firma) of de spanning op het net voor de voeding vh Systeem moet tussen 110 en 230 Volt liggen (bij normaal verbruik).' for subject: [urn:oslo-toolchain:dc5e939857178933df81554e906638a1b5bfde28fd13b98472d6fc93a532cb63](all-thermografische-gebouwanalyse.jsonld#L1478), replace with 'van het'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv onderhoud of de netspanning.' for subject: [urn:oslo-toolchain:ba7d09141c3f9e2ee4e6ba487ca786b3fcdca6f746f95041a4ac642ecfcfa7c9](all-thermografische-gebouwanalyse.jsonld#L1526), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Slaat op de levensduur vh Systeem als geheel of van cruciale delen ervan zoals de batterij en de Condities waaronder die kenmerken gelden. Bv de batterij van het systeem gaat 3 weken mee alvorens ze opnieuw moet worden opgeladen op voorwaarde dat de temperatuur tussen -5 en +35 graden ligt.' for subject: [urn:oslo-toolchain:fda15210d99a1b7d03286cdde99e19652036ef1dbfa485549ac5b9728a1ad583](all-thermografische-gebouwanalyse.jsonld#L1574), replace with 'van het'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Slaat op de levensduur vh Systeem als geheel of van cruciale delen ervan zoals de batterij en de Condities waaronder die kenmerken gelden. Bv de batterij van het systeem gaat 3 weken mee alvorens ze opnieuw moet worden opgeladen op voorwaarde dat de temperatuur tussen -5 en +35 graden ligt.' for subject: [urn:oslo-toolchain:fda15210d99a1b7d03286cdde99e19652036ef1dbfa485549ac5b9728a1ad583](all-thermografische-gebouwanalyse.jsonld#L1574), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv de levensduur van de batterij.' for subject: [urn:oslo-toolchain:7ce3b8d7460aa141d0c0bc7f958dd1dd3c59c72e7d28eab16c39d75568622106](all-thermografische-gebouwanalyse.jsonld#L1622), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'bvb' in sentence 'Bedoeld om kennis te organiseren,bvb in een codelijst of taxonomie (een zgn ConceptScheme). Zie <a href="https://www.w3.org/TR/skos-reference/">SKOS</a> voor meer informatie.' for subject: [urn:oslo-toolchain:d9e63fa0343d384dd2af8fa9f78c7fbda41a3ab5daa0792c76697758a23a876d](all-thermografische-gebouwanalyse.jsonld#L1670), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'bvb' in sentence 'Te gebruiken ipv Concept als een voorgedefinieerde eenheid van QUDT beschikbaar is,bvb <a href="http://qudt.org/vocab/unit/M">meter</a>. Zie <a href="https://www.qudt.org/doc/DOC_VOCAB-UNITS.html">QUDT-units</a> voor meer info.' for subject: [urn:oslo-toolchain:481adc509dbc6e79f7b438bba06bb8cdd47e6ba4498205af5dad72ea75242df8](all-thermografische-gebouwanalyse.jsonld#L1716), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv de opgegeven Nauwkeurigheid van een Sensor die de windsnelheid meet geldt enkel voor windsnelheden tussen 10 en 60 m/s.' for subject: [urn:oslo-toolchain:25863b4e03538ca46f3273a819ec94bba608041e9bf1ee40e15e7bbc1608de77](all-thermografische-gebouwanalyse.jsonld#L1805), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'vd' in sentence 'Type vd string slaat op het identificatiesysteem (incl de versie ervan), de string zelf op de eigenlijke identificator.' for subject: [urn:oslo-toolchain:bbd0b9cafd583f7cbc517c9e90b392ed5cb58b816344971f7a29c516a7842928](all-thermografische-gebouwanalyse.jsonld#L1855), replace with 'van de'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'incl' in sentence 'Type vd string slaat op het identificatiesysteem (incl de versie ervan), de string zelf op de eigenlijke identificator.' for subject: [urn:oslo-toolchain:bbd0b9cafd583f7cbc517c9e90b392ed5cb58b816344971f7a29c516a7842928](all-thermografische-gebouwanalyse.jsonld#L1855), replace with 'inclusief'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'tgv' in sentence 'Vermijdt fouten tgv het opsplitsen ve adres in zijn onderdelen. Geeft de voorgeschreven volgorde vd verschillende onderdelen weer.' for subject: [urn:oslo-toolchain:0556aab78bd3aa8a174ad32c4e745653e354fc79d027fc62c2c503408479dca7](all-thermografische-gebouwanalyse.jsonld#L2577), replace with 'ten gevolge van'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Vermijdt fouten tgv het opsplitsen ve adres in zijn onderdelen. Geeft de voorgeschreven volgorde vd verschillende onderdelen weer.' for subject: [urn:oslo-toolchain:0556aab78bd3aa8a174ad32c4e745653e354fc79d027fc62c2c503408479dca7](all-thermografische-gebouwanalyse.jsonld#L2577), replace with 'van een'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found abbreviation 'vd' in sentence 'Vermijdt fouten tgv het opsplitsen ve adres in zijn onderdelen. Geeft de voorgeschreven volgorde vd verschillende onderdelen weer.' for subject: [urn:oslo-toolchain:0556aab78bd3aa8a174ad32c4e745653e354fc79d027fc62c2c503408479dca7](all-thermografische-gebouwanalyse.jsonld#L2577), replace with 'van de'

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:7f0c0d3e29be7ac495dda6814de3e1932c56967cdc1f8667b5884ac4f5923ae0](all-thermografische-gebouwanalyse.jsonld#L2633)

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:62bc47107094b5011a78797806ed0d963cff62acca7fe332209c10245a514631](all-thermografische-gebouwanalyse.jsonld#L2689)

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:1cb973725b5d3783fecb9b54ee141c613b8e9ad8da7bca0c6f71427372832fcb](all-thermografische-gebouwanalyse.jsonld#L2745)

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:c615b7a2cf1206b3a51c7cf52129034280f99797461afd9adf44f9d8f0309436](all-thermografische-gebouwanalyse.jsonld#L2931)

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:fbc31e3af80ba4fc490aaa978004516d9db2f7ed78acaff44c8e2a93fa157277](all-thermografische-gebouwanalyse.jsonld#L3049)

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:2d33c1fd6375253e9654fc4a408ef02f61e6c72f9fcf862c1317cff616f4dbd0](all-thermografische-gebouwanalyse.jsonld#L3105)

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:fe1a28e047d181c88fe215f982b704bf0baf20e4a0cf62de69b9bd52b273811a](all-thermografische-gebouwanalyse.jsonld#L3164)

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:a8ecca9f7a61f0b807205faebd4f04de1e09088ea830709a7834299003abaa79](all-thermografische-gebouwanalyse.jsonld#L3220)

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:d124d1cf385e58e34edbdce335f51c4bd6bd975dafacf294f4f50b6552c638b7](all-thermografische-gebouwanalyse.jsonld#L3276)

2026-10-08T19:29:00.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:bc9863d45350306d43ca0ed3dc793ab60647e743a41c2bdfe2ca4e2af4ad8e62](all-thermografische-gebouwanalyse.jsonld#L3335)

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'tbv' in sentence 'Specialisatie van Adresvoorstelling:locatieaanduiding tbv Belgische adressen.' for subject: [urn:oslo-toolchain:cb122dd9bc3a0407b62a3cea067243a232d9db681d2c1de146b4994e2672ccc3](all-thermografische-gebouwanalyse.jsonld#L2801), replace with 'ten behoeve van'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'tbv' in sentence 'Specialisatie van Adresvoorstelling:locatieaanduiding tbv Belgische adressen.' for subject: [urn:oslo-toolchain:fbced3b6f179b8fd93f9635f297eae3c1f6a82d574df41c35685a47d7ccc2466](all-thermografische-gebouwanalyse.jsonld#L2866), replace with 'ten behoeve van'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bvb' in sentence 'Bvb de naam vh gehucht waarin het adres ligt.' for subject: [urn:oslo-toolchain:b47c8d694583794d904c41d2aae1cad8780e3292cc7546ed21ab56e108a7f844](all-thermografische-gebouwanalyse.jsonld#L2987), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Bvb de naam vh gehucht waarin het adres ligt.' for subject: [urn:oslo-toolchain:b47c8d694583794d904c41d2aae1cad8780e3292cc7546ed21ab56e108a7f844](all-thermografische-gebouwanalyse.jsonld#L2987), replace with 'van het'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bvb' in sentence 'Het datatype Any is te substitueren door een toepasselijk datatype. Bvb voor een EPC-score een KwantiatieveWaarde met waarde in procent of een skos:Concept met een kwalitatieve waarde (A, B, C etc). Bvb voor onroerend erfgoed een skos:Concept met waarde VastgesteldOnroerendErfgoed of BeschermdOnroerenderfgoed.' for subject: [urn:oslo-toolchain:7d70bd0a4a196014a571c450656124dda5a50e7d11ae44cbaaae25c99a11ec3e](all-thermografische-gebouwanalyse.jsonld#L4847), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'dmv' in sentence 'Beschrijft deze kenmerken dmv punten, lijnen, polygonen en coördinaten.' for subject: [urn:oslo-toolchain:78ae94c9c21b55e255ed89d21a665809121217c669a393230a8034d0d2d1fc98](all-thermografische-gebouwanalyse.jsonld#L7595), replace with 'door middel van'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv als attribuut ve persoon of gebouw... De adresvoorstelling heeft niet enkel betrekking op Belgische adressen, ze kan gebruikt worden om buitenlandse adressen weer te geven (waar mogelijk andere adresaanduidingen dan huisnummer of busnummer worden gebruikt of waar adrescomponenten zoals adresgebieden voorkomen).' for subject: [urn:oslo-toolchain:d3e83e44ee1aa97f14f0d81d29b656ebeb87061f675af953966cdf11588f71fa](all-thermografische-gebouwanalyse.jsonld#L7643), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Bv als attribuut ve persoon of gebouw... De adresvoorstelling heeft niet enkel betrekking op Belgische adressen, ze kan gebruikt worden om buitenlandse adressen weer te geven (waar mogelijk andere adresaanduidingen dan huisnummer of busnummer worden gebruikt of waar adrescomponenten zoals adresgebieden voorkomen).' for subject: [urn:oslo-toolchain:d3e83e44ee1aa97f14f0d81d29b656ebeb87061f675af953966cdf11588f71fa](all-thermografische-gebouwanalyse.jsonld#L7643), replace with 'van een'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'In essentie een waarde en de naam vh type van de waarde. In deze context gaat het over zaken zoals operator, omgevingstemperatuur etc.' for subject: [urn:oslo-toolchain:6cd3bea3448f83a4dd125d0ebf23a25ab24a93a525affadadc68456ccc163fc3](all-thermografische-gebouwanalyse.jsonld#L7685), replace with 'van het'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found sentence without a '.': 'In de context van gebouwen heeft dit betrekking op energetische eigenschappen, typisch voor een specifiek pand' for subject: [urn:oslo-toolchain:ddddd9bbc1f8c8c371220dd2f80302c37a479dfb5cf2589d1ac2bc7baf793d0b](all-thermografische-gebouwanalyse.jsonld#L8110)

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'ttz' in sentence 'Sensoren genereren een resultaat op basis van een Stimulus, ttz een verandering in de omgeving, of op basis van resultaten van andere Observaties. Ze worden typisch gehost door een Platform. Voorbeelden zijn snelheidsmeters, gyroscopen, barometers, magnetometers gemonteerd op een smart phone. Ook bv het menselijk oog kan beschouwd worden als een Sensor.' for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194), replace with 'het is te zeggen'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Sensoren genereren een resultaat op basis van een Stimulus, ttz een verandering in de omgeving, of op basis van resultaten van andere Observaties. Ze worden typisch gehost door een Platform. Voorbeelden zijn snelheidsmeters, gyroscopen, barometers, magnetometers gemonteerd op een smart phone. Ook bv het menselijk oog kan beschouwd worden als een Sensor.' for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Deze componenten kunnen Systemen op zich zijn. In deze context zijn het Systemen die een Observatieprocedure realiseren (typisch een Sensor) of waarmee een Bemonsteringsprocedure wordt uitgevoerd (bv een Boorinstallatie).' for subject: [urn:oslo-toolchain:39c408dc8d6a746c3a0ea674094d0c7c51911017ea6f079ede5a16f8253b19b3](all-thermografische-gebouwanalyse.jsonld#L561), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'ihkv' in sentence 'Relevant ihkv het Renovatieproject, bvb EPC-waarde, isolatiewaarde vh dak, vastgesteld of beschermd onroerend erfgoed etc' for subject: [urn:oslo-toolchain:4f73baa3053dec5de1f4cf9fce3f075072154858d793b5a8c39c2a04c1f60d1b](all-thermografische-gebouwanalyse.jsonld#L729), replace with 'in het kader van'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'bvb' in sentence 'Relevant ihkv het Renovatieproject, bvb EPC-waarde, isolatiewaarde vh dak, vastgesteld of beschermd onroerend erfgoed etc' for subject: [urn:oslo-toolchain:4f73baa3053dec5de1f4cf9fce3f075072154858d793b5a8c39c2a04c1f60d1b](all-thermografische-gebouwanalyse.jsonld#L729), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Relevant ihkv het Renovatieproject, bvb EPC-waarde, isolatiewaarde vh dak, vastgesteld of beschermd onroerend erfgoed etc' for subject: [urn:oslo-toolchain:4f73baa3053dec5de1f4cf9fce3f075072154858d793b5a8c39c2a04c1f60d1b](all-thermografische-gebouwanalyse.jsonld#L729), replace with 'van het'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv Meetbereik,Nauwkeurigheid,Resolutie etc.' for subject: [urn:oslo-toolchain:50391fddb04a006afc5abbff149112f9eed78ef95bd8e67b98f57f99428d5292](all-thermografische-gebouwanalyse.jsonld#L1382), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Slaat op zaken als Meetbereik, Nauwkeurigheid, Afwijking, Resolutie, Responstijd, etc. en de eventuele Condities waaronder die specificaties gelden, bv een Nauwkerigheid van 1mm is gegarandeerd voor afstanden onder de 100 meter.' for subject: [urn:oslo-toolchain:199891c289cfd023c5bc0e399b8e325967f0f232415c3b5a3a4dc9f190b535d2](all-thermografische-gebouwanalyse.jsonld#L1430), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Slaat op zaken als onderhoud of de vereiste netspanning en de eventuele bijkomende condities, bv om de 3 weken is onderhoud nodig (door een gespecialiseerde firma) of de spanning op het net voor de voeding vh Systeem moet tussen 110 en 230 Volt liggen (bij normaal verbruik).' for subject: [urn:oslo-toolchain:dc5e939857178933df81554e906638a1b5bfde28fd13b98472d6fc93a532cb63](all-thermografische-gebouwanalyse.jsonld#L1478), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Slaat op zaken als onderhoud of de vereiste netspanning en de eventuele bijkomende condities, bv om de 3 weken is onderhoud nodig (door een gespecialiseerde firma) of de spanning op het net voor de voeding vh Systeem moet tussen 110 en 230 Volt liggen (bij normaal verbruik).' for subject: [urn:oslo-toolchain:dc5e939857178933df81554e906638a1b5bfde28fd13b98472d6fc93a532cb63](all-thermografische-gebouwanalyse.jsonld#L1478), replace with 'van het'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv onderhoud of de netspanning.' for subject: [urn:oslo-toolchain:ba7d09141c3f9e2ee4e6ba487ca786b3fcdca6f746f95041a4ac642ecfcfa7c9](all-thermografische-gebouwanalyse.jsonld#L1526), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Slaat op de levensduur vh Systeem als geheel of van cruciale delen ervan zoals de batterij en de Condities waaronder die kenmerken gelden. Bv de batterij van het systeem gaat 3 weken mee alvorens ze opnieuw moet worden opgeladen op voorwaarde dat de temperatuur tussen -5 en +35 graden ligt.' for subject: [urn:oslo-toolchain:fda15210d99a1b7d03286cdde99e19652036ef1dbfa485549ac5b9728a1ad583](all-thermografische-gebouwanalyse.jsonld#L1574), replace with 'van het'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Slaat op de levensduur vh Systeem als geheel of van cruciale delen ervan zoals de batterij en de Condities waaronder die kenmerken gelden. Bv de batterij van het systeem gaat 3 weken mee alvorens ze opnieuw moet worden opgeladen op voorwaarde dat de temperatuur tussen -5 en +35 graden ligt.' for subject: [urn:oslo-toolchain:fda15210d99a1b7d03286cdde99e19652036ef1dbfa485549ac5b9728a1ad583](all-thermografische-gebouwanalyse.jsonld#L1574), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv de levensduur van de batterij.' for subject: [urn:oslo-toolchain:7ce3b8d7460aa141d0c0bc7f958dd1dd3c59c72e7d28eab16c39d75568622106](all-thermografische-gebouwanalyse.jsonld#L1622), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv de opgegeven Nauwkeurigheid van een Sensor die de windsnelheid meet geldt enkel voor windsnelheden tussen 10 en 60 m/s.' for subject: [urn:oslo-toolchain:25863b4e03538ca46f3273a819ec94bba608041e9bf1ee40e15e7bbc1608de77](all-thermografische-gebouwanalyse.jsonld#L1805), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'vd' in sentence 'Type vd string slaat op het identificatiesysteem (incl de versie ervan), de string zelf op de eigenlijke identificator.' for subject: [urn:oslo-toolchain:bbd0b9cafd583f7cbc517c9e90b392ed5cb58b816344971f7a29c516a7842928](all-thermografische-gebouwanalyse.jsonld#L1855), replace with 'van de'

2026-10-08T19:29:00.839Z warn: [JsonLdValidationService]: Found abbreviation 'incl' in sentence 'Type vd string slaat op het identificatiesysteem (incl de versie ervan), de string zelf op de eigenlijke identificator.' for subject: [urn:oslo-toolchain:bbd0b9cafd583f7cbc517c9e90b392ed5cb58b816344971f7a29c516a7842928](all-thermografische-gebouwanalyse.jsonld#L1855), replace with 'inclusief'

2026-10-08T19:29:00.840Z warn: [JsonLdValidationService]: Found abbreviation 'tbv' in sentence 'Specialisatie van Adresvoorstelling:locatieaanduiding tbv Belgische adressen.' for subject: [urn:oslo-toolchain:cb122dd9bc3a0407b62a3cea067243a232d9db681d2c1de146b4994e2672ccc3](all-thermografische-gebouwanalyse.jsonld#L2801), replace with 'ten behoeve van'

2026-10-08T19:29:00.840Z warn: [JsonLdValidationService]: Found abbreviation 'tbv' in sentence 'Specialisatie van Adresvoorstelling:locatieaanduiding tbv Belgische adressen.' for subject: [urn:oslo-toolchain:fbced3b6f179b8fd93f9635f297eae3c1f6a82d574df41c35685a47d7ccc2466](all-thermografische-gebouwanalyse.jsonld#L2866), replace with 'ten behoeve van'

2026-10-08T19:29:00.840Z warn: [JsonLdValidationService]: Found abbreviation 'Bvb' in sentence 'Bvb de naam vh gehucht waarin het adres ligt.' for subject: [urn:oslo-toolchain:b47c8d694583794d904c41d2aae1cad8780e3292cc7546ed21ab56e108a7f844](all-thermografische-gebouwanalyse.jsonld#L2987), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.840Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Bvb de naam vh gehucht waarin het adres ligt.' for subject: [urn:oslo-toolchain:b47c8d694583794d904c41d2aae1cad8780e3292cc7546ed21ab56e108a7f844](all-thermografische-gebouwanalyse.jsonld#L2987), replace with 'van het'

2026-10-08T19:29:00.840Z warn: [JsonLdValidationService]: Found abbreviation 'Bvb' in sentence 'Het datatype Resource is te substitueren door een toepasselijk datatype. Bvb voor een EPC-score een KwantiatieveWaarde met waarde in procent of een skos:Concept met een kwalitatieve waarde (A, B, C etc). Bvb voor onroerend erfgoed een skos:Concept met waarde VastgesteldOnroerendErfgoed of BeschermdOnroerenderfgoed.' for subject: [urn:oslo-toolchain:7d70bd0a4a196014a571c450656124dda5a50e7d11ae44cbaaae25c99a11ec3e](all-thermografische-gebouwanalyse.jsonld#L4847), replace with 'bijvoorbeeld'

2026-10-08T19:29:00.840Z warn: [JsonLdValidationService]: Found abbreviation 'dmv' in sentence 'Beschrijft deze kenmerken dmv punten, lijnen, polygonen en coördinaten.' for subject: [urn:oslo-toolchain:78ae94c9c21b55e255ed89d21a665809121217c669a393230a8034d0d2d1fc98](all-thermografische-gebouwanalyse.jsonld#L7595), replace with 'door middel van'

2026-10-08T19:29:00.840Z warn: [JsonLdValidationService]: Found sentence without a '.': 'In de context van gebouwen heeft dit betrekking op energetische eigenschappen, typisch voor een specifiek pand' for subject: [urn:oslo-toolchain:ddddd9bbc1f8c8c371220dd2f80302c37a479dfb5cf2589d1ac2bc7baf793d0b](all-thermografische-gebouwanalyse.jsonld#L8110)

2026-10-08T19:29:00.841Z warn: [JsonLdValidationService]: Labels must only contain alphabetical characters: 'BIM_Gebouw' for subject: [urn:oslo-toolchain:abb4b0e6ef8d096b8fb5ef18795462129d9a0b583355f36171d55e1dca66f2d8](all-thermografische-gebouwanalyse.jsonld#L1023)

2026-10-08T19:29:00.841Z warn: [JsonLdValidationService]: Labels must only contain alphabetical characters: 'BIM_Element' for subject: [urn:oslo-toolchain:32198f90e52bc4aaf21073d249362761dab0ed51f36dd220959220be2b4cf88f](all-thermografische-gebouwanalyse.jsonld#L1070)

2026-10-08T19:29:00.842Z warn: [JsonLdValidationService]: Labels must only contain alphabetical characters: 'BIM_Gebouw' for subject: [urn:oslo-toolchain:abb4b0e6ef8d096b8fb5ef18795462129d9a0b583355f36171d55e1dca66f2d8](all-thermografische-gebouwanalyse.jsonld#L1023)

2026-10-08T19:29:00.842Z warn: [JsonLdValidationService]: Labels must only contain alphabetical characters: 'BIM_Element' for subject: [urn:oslo-toolchain:32198f90e52bc4aaf21073d249362761dab0ed51f36dd220959220be2b4cf88f](all-thermografische-gebouwanalyse.jsonld#L1070)

2026-10-08T19:29:00.844Z error: [JsonLdValidationService]: Found missing class or attribute (Toestel): [urn:oslo-toolchain:005f9528c72fe38c8c6ea516c64b0eda6eba1db9b42515152f9fadd19d8aa0c3](all-thermografische-gebouwanalyse.jsonld#L7829) in Application Profile

2026-10-08T19:29:00.844Z error: [JsonLdValidationService]: Found missing class or attribute (Platform): [urn:oslo-toolchain:23a58ad8b235a857a57704dbcc3c0cd5c747cb2cd22676d275df8932f7342f91](all-thermografische-gebouwanalyse.jsonld#L7852) in Application Profile

2026-10-08T19:29:00.844Z error: [JsonLdValidationService]: Found missing class or attribute (Informatieobject): [urn:oslo-toolchain:addceca7e2b26c4bb64465b579fa9f5655f23bd84c856213c42a502d4fcc29c4](all-thermografische-gebouwanalyse.jsonld#L7980) in Application Profile

2026-10-08T19:29:00.850Z info: [JsonLdValidationService]: Validation found 10 non-whitelisted assigned URIs

2026-10-08T19:29:00.850Z info: [JsonLdValidationService]: Validation found 104 sentences with spelling mistakes or abbreviations.

2026-10-08T19:29:00.850Z info: [JsonLdValidationService]: Validation found 4 labels with spelling mistakes or abbreviations.

2026-10-08T19:29:00.850Z info: [JsonLdValidationService]: Validation successful! All base URIs seem to be valid.

2026-10-08T19:29:00.850Z info: [JsonLdValidationService]: Validation found 3 missing referenced classes or attributes.

#||# oslo-jsonld-validator   

#||# -------------------------------------  

#||# command: oslo-jsonld-validator --input /tmp/workspace/report4/doc/applicatieprofiel/thermografische-gebouwanalyse/kandidaatstandaard/2025-05-22/all-thermografische-gebouwanalyse.jsonld --whitelist https://raw.githubusercontent.com/Informatievlaanderen/OSLO-UML-Transformer/refs/heads/configuration/whitelist.json --specificationType ApplicationProfile --publicationEnvironment data.vlaanderen.be --language nl  

2026-10-08T19:29:01.598Z info: [JsonLdValidationService]: Loaded 56 URI prefixes into whitelist

2026-10-08T19:29:01.830Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://www.w3.org/ns/sosa/Sensor for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194)

2026-10-08T19:29:01.830Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://www.w3.org/ns/sosa/Platform for subject: [urn:oslo-toolchain:23a58ad8b235a857a57704dbcc3c0cd5c747cb2cd22676d275df8932f7342f91](all-thermografische-gebouwanalyse.jsonld#L7852)

2026-10-08T19:29:01.830Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://www.w3.org/ns/sosa/Platform for subject: [urn:oslo-toolchain:4147b673ade81ea458b13e54e597c07bbc614dd4cf8fedc06f72c69bafdc25ba](all-thermografische-gebouwanalyse.jsonld#L7941)

2026-10-08T19:29:01.830Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://www.w3.org/ns/sosa/Platform for subject: [urn:oslo-toolchain:2118013347bed818023bde628fb75fa16625423a5ebe2bbda5d96028b950a19d](all-thermografische-gebouwanalyse.jsonld#L645)

2026-10-08T19:29:01.830Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://qudt.org/schema/qudt/Unit for subject: [urn:oslo-toolchain:481adc509dbc6e79f7b438bba06bb8cdd47e6ba4498205af5dad72ea75242df8](all-thermografische-gebouwanalyse.jsonld#L1716)

2026-10-08T19:29:01.830Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://qudt.org/schema/qudt/value for subject: [urn:oslo-toolchain:29cc3e1a71eb3ab20c073b6685187a06633c3d3c619249eb9ecceb1741fd1696](all-thermografische-gebouwanalyse.jsonld#L3535)

2026-10-08T19:29:01.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://dbpedia.org/ontology/influencedBy for subject: [urn:oslo-toolchain:a603925495c15a3c3354f7723e65a8a0c91513af02e261c4811458579fee6d87](all-thermografische-gebouwanalyse.jsonld#L4091)

2026-10-08T19:29:01.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://qudt.org/schema/qudt/hasUnit for subject: [urn:oslo-toolchain:ad8ddd7aec0b15c51570083cf5dd46bd29b325443d23f5c20b8cb73f04c21fb7](all-thermografische-gebouwanalyse.jsonld#L6159)

2026-10-08T19:29:01.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://www.w3.org/ns/sosa/hosts for subject: [urn:oslo-toolchain:ccb5981ce5dced486c6f2c2c725f307a756bd3baf7de00e673bffab585bc8250](all-thermografische-gebouwanalyse.jsonld#L6859)

2026-10-08T19:29:01.831Z warn: [JsonLdValidationService]: Found non-whitelisted assigned URI: https://qudt.org/schema/qudt/QuantityValue for subject: [urn:oslo-toolchain:25161675a715b914d0c25907081fb9b998a12c8886c2b563ec7e88a6ac054eb7](all-thermografische-gebouwanalyse.jsonld#L7721)

2026-10-08T19:29:01.833Z warn: [JsonLdValidationService]: Found abbreviation 'incl' in sentence 'Toestel of Agent (incl Personen of software) waarmee Observaties gemaakt worden.' for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194), replace with 'inclusief'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 'dmv' in sentence 'Reeks van stilstaande beelden die snel achter elkaar worden afgespeeld om de illusie van beweging te creëren, vastgelegd dmv een videocamera of bekomen door animatie.' for subject: [[urn:oslo-toolchain:4b3c53866efe16fefd4e6e8a25a568e53340d55f1be93e1422231d1eedc54f34](all-thermografische-gebouwanalyse.jsonld#L7991)](all-thermografische-gebouwanalyse.jsonld#L1117), replace with 'door middel van'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Capaciteit ve Systeem.' for subject: [urn:oslo-toolchain:50391fddb04a006afc5abbff149112f9eed78ef95bd8e67b98f57f99428d5292](all-thermografische-gebouwanalyse.jsonld#L1382), replace with 'van een'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Capaciteiten ve Systeem.' for subject: [urn:oslo-toolchain:199891c289cfd023c5bc0e399b8e325967f0f232415c3b5a3a4dc9f190b535d2](all-thermografische-gebouwanalyse.jsonld#L1430), replace with 'van een'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Levensduur ve Systeem.' for subject: [urn:oslo-toolchain:fda15210d99a1b7d03286cdde99e19652036ef1dbfa485549ac5b9728a1ad583](all-thermografische-gebouwanalyse.jsonld#L1574), replace with 'van een'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 'ttz' in sentence 'Immaterieel object dat informatie omvat, ttz gegevens of data waaraan op één of andere manier betekenis is gegeven. Een Informatieobject gaat ergens over (het is propositioneel) en brengt dat over dmv symbolen (karakters, tekens etc.) of aggregaties daarvan.' for subject: [urn:oslo-toolchain:f0249a8683cc17b376b4c2965640c06ecc88fb4bdc6db243e30638ea2b3e6fe4](all-thermografische-gebouwanalyse.jsonld#L1763), replace with 'het is te zeggen'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 'dmv' in sentence 'Immaterieel object dat informatie omvat, ttz gegevens of data waaraan op één of andere manier betekenis is gegeven. Een Informatieobject gaat ergens over (het is propositioneel) en brengt dat over dmv symbolen (karakters, tekens etc.) of aggregaties daarvan.' for subject: [urn:oslo-toolchain:f0249a8683cc17b376b4c2965640c06ecc88fb4bdc6db243e30638ea2b3e6fe4](all-thermografische-gebouwanalyse.jsonld#L1763), replace with 'door middel van'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 'dmv' in sentence 'Positie in de tijd uitgedrukt dmv xsd:dateTime.' for subject: [urn:oslo-toolchain:a398b95cef8dd002613d6ce0e52a16214c004460c7a39f561a1b940b4ffc1592](all-thermografische-gebouwanalyse.jsonld#L1967), replace with 'door middel van'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Naam vh model vh Toestel.' for subject: [urn:oslo-toolchain:7420a01e01dbb4fb76f2572ff2ebe5cb315132dd80c8706dd60b91581551c0e8](all-thermografische-gebouwanalyse.jsonld#L2067), replace with 'van het'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Naam van het model' for subject: [urn:oslo-toolchain:eb9c2c41a935014dca30a0bde5fb850d2c47f4a8be246140388ebdc97ebb118b](all-thermografische-gebouwanalyse.jsonld#L2167)

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Straatnaam vh adres.' for subject: [urn:oslo-toolchain:62bc47107094b5011a78797806ed0d963cff62acca7fe332209c10245a514631](all-thermografische-gebouwanalyse.jsonld#L2689), replace with 'van het'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Naam of omschrijving vh het geografisch object dat de adreslocator aanduidt.' for subject: [urn:oslo-toolchain:c615b7a2cf1206b3a51c7cf52129034280f99797461afd9adf44f9d8f0309436](all-thermografische-gebouwanalyse.jsonld#L2931), replace with 'van het'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Naam ve geografisch gebied of plaats die een aantal adresseerbare objecten groepeert om deze te adresseren zonder dat het gebied of de plaats een administratieve eenheid is' for subject: [urn:oslo-toolchain:b47c8d694583794d904c41d2aae1cad8780e3292cc7546ed21ab56e108a7f844](all-thermografische-gebouwanalyse.jsonld#L2987), replace with 'van een'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Gemeentenaam vh adres.' for subject: [urn:oslo-toolchain:2d33c1fd6375253e9654fc4a408ef02f61e6c72f9fcf862c1317cff616f4dbd0](all-thermografische-gebouwanalyse.jsonld#L3105), replace with 'van het'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'De regio vh adres, doorgaans een provincie of deelstaat of gelijkaardig gebied dat typisch meerdere plaatsen omvat.' for subject: [urn:oslo-toolchain:fe1a28e047d181c88fe215f982b704bf0baf20e4a0cf62de69b9bd52b273811a](all-thermografische-gebouwanalyse.jsonld#L3164), replace with 'van het'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Hoogste administratieve eenheid vh adres, doorgaans een land.' for subject: [urn:oslo-toolchain:a8ecca9f7a61f0b807205faebd4f04de1e09088ea830709a7834299003abaa79](all-thermografische-gebouwanalyse.jsonld#L3220), replace with 'van het'

2026-10-08T19:29:01.834Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Naam vh type van de waarde.' for subject: [urn:oslo-toolchain:b7096add1860ac1b55bc980d96333c3b18a1f5a00e1b680e2de1fce5e1255472](all-thermografische-gebouwanalyse.jsonld#L3491), replace with 'van het'

2026-10-08T19:29:01.835Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Bepaalde hoeveelheid' for subject: [urn:oslo-toolchain:29cc3e1a71eb3ab20c073b6685187a06633c3d3c619249eb9ecceb1741fd1696](all-thermografische-gebouwanalyse.jsonld#L3535)

2026-10-08T19:29:01.835Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Einde ve Temporele Entiteit.' for subject: [urn:oslo-toolchain:b520bc226e344e25deca7cd6bd9458a7588d413d7fbf390518c67802cb16ecef](all-thermografische-gebouwanalyse.jsonld#L4147), replace with 'van een'

2026-10-08T19:29:01.835Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Start ve Temporele Entiteit.' for subject: [urn:oslo-toolchain:783f89885bbc75afac686efd099fa544215f6eefa8ba2627a95ea13b80926c77](all-thermografische-gebouwanalyse.jsonld#L4297), replace with 'van een'

2026-10-08T19:29:01.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Aard vh Systeem.' for subject: [urn:oslo-toolchain:74ad9e0fa03d3285ed5c9e15be925f98e246b279ffbc78e03d74d90b93241bbc](all-thermografische-gebouwanalyse.jsonld#L4447), replace with 'van het'

2026-10-08T19:29:01.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Capaciteit vh Systeem.' for subject: [urn:oslo-toolchain:b1de2524807d7078cdb4b6a2274127db4dd2ffa767f4e41f6d6b1da54507d8c9](all-thermografische-gebouwanalyse.jsonld#L4497), replace with 'van het'

2026-10-08T19:29:01.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Werking vh Systeem.' for subject: [urn:oslo-toolchain:583605ad824d939144f7f83e364078cc4854da8e8ddacc3e8b762f8fc6cdef73](all-thermografische-gebouwanalyse.jsonld#L4547), replace with 'van het'

2026-10-08T19:29:01.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Levensduur vh Systeem.' for subject: [urn:oslo-toolchain:450c3e98d9092cf62a1c5f4e4c0652ae5cbecb1f783a9d2aef14da10c4cb600b](all-thermografische-gebouwanalyse.jsonld#L4597), replace with 'van het'

2026-10-08T19:29:01.835Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Aard vh Platform.' for subject: [urn:oslo-toolchain:092cfc640b8c07d1f682396f27cc3ad742422fe9ed628b130162e84edc7fe3ee](all-thermografische-gebouwanalyse.jsonld#L4647), replace with 'van het'

2026-10-08T19:29:01.835Z warn: [JsonLdValidationService]: Found abbreviation 'vd' in sentence 'De fenomeentijd vd Observaties.' for subject: [urn:oslo-toolchain:01ff43a785c669dbee16d3f2751d0ce642918da61c13b45ac71dcde5b31f4ca7](all-thermografische-gebouwanalyse.jsonld#L5459), replace with 'van de'

2026-10-08T19:29:01.835Z warn: [JsonLdValidationService]: Found abbreviation 'ttz' in sentence 'Temporele Entiteit waarvan de omvang en duurtijd verschilt van nul, ttz waarvoor de begin- en eindtijd verschillend zijn.' for subject: [urn:oslo-toolchain:8cbf65d213c6a1aa3cfcfc2726b923ce9574e92917de59bde4dc246fc9a0b83f](all-thermografische-gebouwanalyse.jsonld#L7554), replace with 'het is te zeggen'

2026-10-08T19:29:01.835Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Eigenschap die iedereen in een groep heeft' for subject: [urn:oslo-toolchain:ddddd9bbc1f8c8c371220dd2f80302c37a479dfb5cf2589d1ac2bc7baf793d0b](all-thermografische-gebouwanalyse.jsonld#L8110)

2026-10-08T19:29:01.835Z warn: [JsonLdValidationService]: Found abbreviation 'incl' in sentence 'Toestel of Agent (incl Personen of software) waarmee Observaties gemaakt worden.' for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194), replace with 'inclusief'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Domeinobject' for subject: [urn:oslo-toolchain:abb4b0e6ef8d096b8fb5ef18795462129d9a0b583355f36171d55e1dca66f2d8](all-thermografische-gebouwanalyse.jsonld#L1023)

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Capaciteit ve Systeem.' for subject: [urn:oslo-toolchain:50391fddb04a006afc5abbff149112f9eed78ef95bd8e67b98f57f99428d5292](all-thermografische-gebouwanalyse.jsonld#L1382), replace with 'van een'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Capaciteiten ve Systeem.' for subject: [urn:oslo-toolchain:199891c289cfd023c5bc0e399b8e325967f0f232415c3b5a3a4dc9f190b535d2](all-thermografische-gebouwanalyse.jsonld#L1430), replace with 'van een'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Levensduur ve Systeem.' for subject: [urn:oslo-toolchain:fda15210d99a1b7d03286cdde99e19652036ef1dbfa485549ac5b9728a1ad583](all-thermografische-gebouwanalyse.jsonld#L1574), replace with 'van een'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Holistisch en/of theoretisch begrip van een product' for subject: [urn:oslo-toolchain:d9e63fa0343d384dd2af8fa9f78c7fbda41a3ab5daa0792c76697758a23a876d](all-thermografische-gebouwanalyse.jsonld#L1670)

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 'dmv' in sentence 'Positie in de tijd uitgedrukt dmv xsd:dateTime.' for subject: [urn:oslo-toolchain:a398b95cef8dd002613d6ce0e52a16214c004460c7a39f561a1b940b4ffc1592](all-thermografische-gebouwanalyse.jsonld#L1967), replace with 'door middel van'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Naam vh model vh Toestel.' for subject: [urn:oslo-toolchain:7420a01e01dbb4fb76f2572ff2ebe5cb315132dd80c8706dd60b91581551c0e8](all-thermografische-gebouwanalyse.jsonld#L2067), replace with 'van het'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Naam van het model' for subject: [urn:oslo-toolchain:eb9c2c41a935014dca30a0bde5fb850d2c47f4a8be246140388ebdc97ebb118b](all-thermografische-gebouwanalyse.jsonld#L2167)

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Straatnaam vh adres.' for subject: [urn:oslo-toolchain:62bc47107094b5011a78797806ed0d963cff62acca7fe332209c10245a514631](all-thermografische-gebouwanalyse.jsonld#L2689), replace with 'van het'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Naam of omschrijving vh het geografisch object dat de adreslocator aanduidt.' for subject: [urn:oslo-toolchain:c615b7a2cf1206b3a51c7cf52129034280f99797461afd9adf44f9d8f0309436](all-thermografische-gebouwanalyse.jsonld#L2931), replace with 'van het'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Naam ve geografisch gebied of plaats die een aantal adresseerbare objecten groepeert om deze te adresseren zonder dat het gebied of de plaats een administratieve eenheid is' for subject: [urn:oslo-toolchain:b47c8d694583794d904c41d2aae1cad8780e3292cc7546ed21ab56e108a7f844](all-thermografische-gebouwanalyse.jsonld#L2987), replace with 'van een'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Gemeentenaam vh adres.' for subject: [urn:oslo-toolchain:2d33c1fd6375253e9654fc4a408ef02f61e6c72f9fcf862c1317cff616f4dbd0](all-thermografische-gebouwanalyse.jsonld#L3105), replace with 'van het'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'De regio vh adres, doorgaans een provincie of deelstaat of gelijkaardig gebied dat typisch meerdere plaatsen omvat.' for subject: [urn:oslo-toolchain:fe1a28e047d181c88fe215f982b704bf0baf20e4a0cf62de69b9bd52b273811a](all-thermografische-gebouwanalyse.jsonld#L3164), replace with 'van het'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Hoogste Administratieve eenheid vh adres, doorgaans een land.' for subject: [urn:oslo-toolchain:a8ecca9f7a61f0b807205faebd4f04de1e09088ea830709a7834299003abaa79](all-thermografische-gebouwanalyse.jsonld#L3220), replace with 'van het'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Bepaalde hoeveelheid' for subject: [urn:oslo-toolchain:29cc3e1a71eb3ab20c073b6685187a06633c3d3c619249eb9ecceb1741fd1696](all-thermografische-gebouwanalyse.jsonld#L3535)

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Einde ve TemporeleEntiteit.' for subject: [urn:oslo-toolchain:b520bc226e344e25deca7cd6bd9458a7588d413d7fbf390518c67802cb16ecef](all-thermografische-gebouwanalyse.jsonld#L4147), replace with 'van een'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Start ve TemporeleEntiteit.' for subject: [urn:oslo-toolchain:783f89885bbc75afac686efd099fa544215f6eefa8ba2627a95ea13b80926c77](all-thermografische-gebouwanalyse.jsonld#L4297), replace with 'van een'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Aard vh Systeem.' for subject: [urn:oslo-toolchain:74ad9e0fa03d3285ed5c9e15be925f98e246b279ffbc78e03d74d90b93241bbc](all-thermografische-gebouwanalyse.jsonld#L4447), replace with 'van het'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Capaciteit vh Systeem.' for subject: [urn:oslo-toolchain:b1de2524807d7078cdb4b6a2274127db4dd2ffa767f4e41f6d6b1da54507d8c9](all-thermografische-gebouwanalyse.jsonld#L4497), replace with 'van het'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Werking vh Systeem.' for subject: [urn:oslo-toolchain:583605ad824d939144f7f83e364078cc4854da8e8ddacc3e8b762f8fc6cdef73](all-thermografische-gebouwanalyse.jsonld#L4547), replace with 'van het'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Levensduur vh Systeem.' for subject: [urn:oslo-toolchain:450c3e98d9092cf62a1c5f4e4c0652ae5cbecb1f783a9d2aef14da10c4cb600b](all-thermografische-gebouwanalyse.jsonld#L4597), replace with 'van het'

2026-10-08T19:29:01.836Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Aard vh Platform.' for subject: [urn:oslo-toolchain:092cfc640b8c07d1f682396f27cc3ad742422fe9ed628b130162e84edc7fe3ee](all-thermografische-gebouwanalyse.jsonld#L4647), replace with 'van het'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'vd' in sentence 'De fenomeentijd vd Observaties.' for subject: [urn:oslo-toolchain:01ff43a785c669dbee16d3f2751d0ce642918da61c13b45ac71dcde5b31f4ca7](all-thermografische-gebouwanalyse.jsonld#L5459), replace with 'van de'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'ttz' in sentence 'TemporeleEntiteit waarvan de omvang en duurtijd verschilt van nul,ttz waarvoor de begin- en eindwaarde verschillend zijn.' for subject: [urn:oslo-toolchain:8cbf65d213c6a1aa3cfcfc2726b923ce9574e92917de59bde4dc246fc9a0b83f](all-thermografische-gebouwanalyse.jsonld#L7554), replace with 'het is te zeggen'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found sentence without a '.': 'Eigenschap die iedereen in een groep heeft' for subject: [urn:oslo-toolchain:ddddd9bbc1f8c8c371220dd2f80302c37a479dfb5cf2589d1ac2bc7baf793d0b](all-thermografische-gebouwanalyse.jsonld#L8110)

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'ttz' in sentence 'Sensoren genereren een resultaat op basis van een Stimulus, ttz een verandering in de omgeving, of op basis van resultaten van andere Observaties. Ze worden typisch gehost door een Platform. Voorbeelden zijn snelheidsmeters, gyroscopen, barometers, magnetometers gemonteerd op een smart phone. Ook bv het menselijk oog kan beschouwd worden als een Sensor.' for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194), replace with 'het is te zeggen'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Sensoren genereren een resultaat op basis van een Stimulus, ttz een verandering in de omgeving, of op basis van resultaten van andere Observaties. Ze worden typisch gehost door een Platform. Voorbeelden zijn snelheidsmeters, gyroscopen, barometers, magnetometers gemonteerd op een smart phone. Ook bv het menselijk oog kan beschouwd worden als een Sensor.' for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Deze componenten kunnen Systemen op zich zijn. In deze context zijn het Systemen die een Observatieprocedure realiseren (typisch een Sensor) of waarmee een Bemonsteringsprocedure wordt uitgevoerd (bv een Boorinstallatie).' for subject: [urn:oslo-toolchain:f38bd27a6af42cda44c7d1c555a0fba428f20865a9edc7713dd0458de38d10c9](all-thermografische-gebouwanalyse.jsonld#L7902), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Deze componenten kunnen Systemen op zich zijn. In deze context zijn het Systemen die een Observatieprocedure realiseren (typisch een Sensor) of waarmee een Bemonsteringsprocedure wordt uitgevoerd (bv een Boorinstallatie).' for subject: [urn:oslo-toolchain:39c408dc8d6a746c3a0ea674094d0c7c51911017ea6f079ede5a16f8253b19b3](all-thermografische-gebouwanalyse.jsonld#L561), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'ihkv' in sentence 'Relevant ihkv het Renovatieproject, bvb EPC-waarde, isolatiewaarde vh dak, vastgesteld of beschermd onroerend erfgoed etc' for subject: [urn:oslo-toolchain:4f73baa3053dec5de1f4cf9fce3f075072154858d793b5a8c39c2a04c1f60d1b](all-thermografische-gebouwanalyse.jsonld#L729), replace with 'in het kader van'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'bvb' in sentence 'Relevant ihkv het Renovatieproject, bvb EPC-waarde, isolatiewaarde vh dak, vastgesteld of beschermd onroerend erfgoed etc' for subject: [urn:oslo-toolchain:4f73baa3053dec5de1f4cf9fce3f075072154858d793b5a8c39c2a04c1f60d1b](all-thermografische-gebouwanalyse.jsonld#L729), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Relevant ihkv het Renovatieproject, bvb EPC-waarde, isolatiewaarde vh dak, vastgesteld of beschermd onroerend erfgoed etc' for subject: [urn:oslo-toolchain:4f73baa3053dec5de1f4cf9fce3f075072154858d793b5a8c39c2a04c1f60d1b](all-thermografische-gebouwanalyse.jsonld#L729), replace with 'van het'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv Observaties die op hetzelfde tijdstip plaatsvonden of hetzelfde Object observeren of door dezelfde sensor zijn gemaakt.' for subject: [urn:oslo-toolchain:1446cd31d631b3eb46805a849b7917659f0ef0af67f095b18626f94954f7fad4](all-thermografische-gebouwanalyse.jsonld#L937), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv Meetbereik,Nauwkeurigheid,Resolutie etc.' for subject: [urn:oslo-toolchain:50391fddb04a006afc5abbff149112f9eed78ef95bd8e67b98f57f99428d5292](all-thermografische-gebouwanalyse.jsonld#L1382), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Slaat op zaken als Meetbereik, Nauwkeurigheid, Afwijking, Resolutie, Responstijd, etc. en de eventuele Condities waaronder die specificaties gelden, bv een Nauwkerigheid van 1mm is gegarandeerd voor afstanden onder de 100 meter.' for subject: [urn:oslo-toolchain:199891c289cfd023c5bc0e399b8e325967f0f232415c3b5a3a4dc9f190b535d2](all-thermografische-gebouwanalyse.jsonld#L1430), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Slaat op zaken als onderhoud of de vereiste netspanning en de eventuele bijkomende condities, bv om de 3 weken is onderhoud nodig (door een gespecialiseerde firma) of de spanning op het net voor de voeding vh Systeem moet tussen 110 en 230 Volt liggen (bij normaal verbruik).' for subject: [urn:oslo-toolchain:dc5e939857178933df81554e906638a1b5bfde28fd13b98472d6fc93a532cb63](all-thermografische-gebouwanalyse.jsonld#L1478), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Slaat op zaken als onderhoud of de vereiste netspanning en de eventuele bijkomende condities, bv om de 3 weken is onderhoud nodig (door een gespecialiseerde firma) of de spanning op het net voor de voeding vh Systeem moet tussen 110 en 230 Volt liggen (bij normaal verbruik).' for subject: [urn:oslo-toolchain:dc5e939857178933df81554e906638a1b5bfde28fd13b98472d6fc93a532cb63](all-thermografische-gebouwanalyse.jsonld#L1478), replace with 'van het'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv onderhoud of de netspanning.' for subject: [urn:oslo-toolchain:ba7d09141c3f9e2ee4e6ba487ca786b3fcdca6f746f95041a4ac642ecfcfa7c9](all-thermografische-gebouwanalyse.jsonld#L1526), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Slaat op de levensduur vh Systeem als geheel of van cruciale delen ervan zoals de batterij en de Condities waaronder die kenmerken gelden. Bv de batterij van het systeem gaat 3 weken mee alvorens ze opnieuw moet worden opgeladen op voorwaarde dat de temperatuur tussen -5 en +35 graden ligt.' for subject: [urn:oslo-toolchain:fda15210d99a1b7d03286cdde99e19652036ef1dbfa485549ac5b9728a1ad583](all-thermografische-gebouwanalyse.jsonld#L1574), replace with 'van het'

2026-10-08T19:29:01.837Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Slaat op de levensduur vh Systeem als geheel of van cruciale delen ervan zoals de batterij en de Condities waaronder die kenmerken gelden. Bv de batterij van het systeem gaat 3 weken mee alvorens ze opnieuw moet worden opgeladen op voorwaarde dat de temperatuur tussen -5 en +35 graden ligt.' for subject: [urn:oslo-toolchain:fda15210d99a1b7d03286cdde99e19652036ef1dbfa485549ac5b9728a1ad583](all-thermografische-gebouwanalyse.jsonld#L1574), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv de levensduur van de batterij.' for subject: [urn:oslo-toolchain:7ce3b8d7460aa141d0c0bc7f958dd1dd3c59c72e7d28eab16c39d75568622106](all-thermografische-gebouwanalyse.jsonld#L1622), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'bvb' in sentence 'Bedoeld om kennis te organiseren,bvb in een codelijst of taxonomie (een zgn ConceptScheme). Zie <a href="https://www.w3.org/TR/skos-reference/">SKOS</a> voor meer informatie.' for subject: [urn:oslo-toolchain:d9e63fa0343d384dd2af8fa9f78c7fbda41a3ab5daa0792c76697758a23a876d](all-thermografische-gebouwanalyse.jsonld#L1670), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'bvb' in sentence 'Te gebruiken ipv Concept als een voorgedefinieerde eenheid van QUDT beschikbaar is,bvb <a href="http://qudt.org/vocab/unit/M">meter</a>. Zie <a href="https://www.qudt.org/doc/DOC_VOCAB-UNITS.html">QUDT-units</a> voor meer info.' for subject: [urn:oslo-toolchain:481adc509dbc6e79f7b438bba06bb8cdd47e6ba4498205af5dad72ea75242df8](all-thermografische-gebouwanalyse.jsonld#L1716), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv de opgegeven Nauwkeurigheid van een Sensor die de windsnelheid meet geldt enkel voor windsnelheden tussen 10 en 60 m/s.' for subject: [urn:oslo-toolchain:25863b4e03538ca46f3273a819ec94bba608041e9bf1ee40e15e7bbc1608de77](all-thermografische-gebouwanalyse.jsonld#L1805), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'vd' in sentence 'Type vd string slaat op het identificatiesysteem (incl de versie ervan), de string zelf op de eigenlijke identificator.' for subject: [urn:oslo-toolchain:bbd0b9cafd583f7cbc517c9e90b392ed5cb58b816344971f7a29c516a7842928](all-thermografische-gebouwanalyse.jsonld#L1855), replace with 'van de'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'incl' in sentence 'Type vd string slaat op het identificatiesysteem (incl de versie ervan), de string zelf op de eigenlijke identificator.' for subject: [urn:oslo-toolchain:bbd0b9cafd583f7cbc517c9e90b392ed5cb58b816344971f7a29c516a7842928](all-thermografische-gebouwanalyse.jsonld#L1855), replace with 'inclusief'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'tgv' in sentence 'Vermijdt fouten tgv het opsplitsen ve adres in zijn onderdelen. Geeft de voorgeschreven volgorde vd verschillende onderdelen weer.' for subject: [urn:oslo-toolchain:0556aab78bd3aa8a174ad32c4e745653e354fc79d027fc62c2c503408479dca7](all-thermografische-gebouwanalyse.jsonld#L2577), replace with 'ten gevolge van'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Vermijdt fouten tgv het opsplitsen ve adres in zijn onderdelen. Geeft de voorgeschreven volgorde vd verschillende onderdelen weer.' for subject: [urn:oslo-toolchain:0556aab78bd3aa8a174ad32c4e745653e354fc79d027fc62c2c503408479dca7](all-thermografische-gebouwanalyse.jsonld#L2577), replace with 'van een'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'vd' in sentence 'Vermijdt fouten tgv het opsplitsen ve adres in zijn onderdelen. Geeft de voorgeschreven volgorde vd verschillende onderdelen weer.' for subject: [urn:oslo-toolchain:0556aab78bd3aa8a174ad32c4e745653e354fc79d027fc62c2c503408479dca7](all-thermografische-gebouwanalyse.jsonld#L2577), replace with 'van de'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:7f0c0d3e29be7ac495dda6814de3e1932c56967cdc1f8667b5884ac4f5923ae0](all-thermografische-gebouwanalyse.jsonld#L2633)

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:62bc47107094b5011a78797806ed0d963cff62acca7fe332209c10245a514631](all-thermografische-gebouwanalyse.jsonld#L2689)

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:1cb973725b5d3783fecb9b54ee141c613b8e9ad8da7bca0c6f71427372832fcb](all-thermografische-gebouwanalyse.jsonld#L2745)

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:c615b7a2cf1206b3a51c7cf52129034280f99797461afd9adf44f9d8f0309436](all-thermografische-gebouwanalyse.jsonld#L2931)

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:fbc31e3af80ba4fc490aaa978004516d9db2f7ed78acaff44c8e2a93fa157277](all-thermografische-gebouwanalyse.jsonld#L3049)

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:2d33c1fd6375253e9654fc4a408ef02f61e6c72f9fcf862c1317cff616f4dbd0](all-thermografische-gebouwanalyse.jsonld#L3105)

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:fe1a28e047d181c88fe215f982b704bf0baf20e4a0cf62de69b9bd52b273811a](all-thermografische-gebouwanalyse.jsonld#L3164)

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:a8ecca9f7a61f0b807205faebd4f04de1e09088ea830709a7834299003abaa79](all-thermografische-gebouwanalyse.jsonld#L3220)

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:d124d1cf385e58e34edbdce335f51c4bd6bd975dafacf294f4f50b6552c638b7](all-thermografische-gebouwanalyse.jsonld#L3276)

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found empty sentence for subject: [urn:oslo-toolchain:bc9863d45350306d43ca0ed3dc793ab60647e743a41c2bdfe2ca4e2af4ad8e62](all-thermografische-gebouwanalyse.jsonld#L3335)

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'tbv' in sentence 'Specialisatie van Adresvoorstelling:locatieaanduiding tbv Belgische adressen.' for subject: [urn:oslo-toolchain:cb122dd9bc3a0407b62a3cea067243a232d9db681d2c1de146b4994e2672ccc3](all-thermografische-gebouwanalyse.jsonld#L2801), replace with 'ten behoeve van'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'tbv' in sentence 'Specialisatie van Adresvoorstelling:locatieaanduiding tbv Belgische adressen.' for subject: [urn:oslo-toolchain:fbced3b6f179b8fd93f9635f297eae3c1f6a82d574df41c35685a47d7ccc2466](all-thermografische-gebouwanalyse.jsonld#L2866), replace with 'ten behoeve van'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'Bvb' in sentence 'Bvb de naam vh gehucht waarin het adres ligt.' for subject: [urn:oslo-toolchain:b47c8d694583794d904c41d2aae1cad8780e3292cc7546ed21ab56e108a7f844](all-thermografische-gebouwanalyse.jsonld#L2987), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Bvb de naam vh gehucht waarin het adres ligt.' for subject: [urn:oslo-toolchain:b47c8d694583794d904c41d2aae1cad8780e3292cc7546ed21ab56e108a7f844](all-thermografische-gebouwanalyse.jsonld#L2987), replace with 'van het'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'Bvb' in sentence 'Het datatype Any is te substitueren door een toepasselijk datatype. Bvb voor een EPC-score een KwantiatieveWaarde met waarde in procent of een skos:Concept met een kwalitatieve waarde (A, B, C etc). Bvb voor onroerend erfgoed een skos:Concept met waarde VastgesteldOnroerendErfgoed of BeschermdOnroerenderfgoed.' for subject: [urn:oslo-toolchain:7d70bd0a4a196014a571c450656124dda5a50e7d11ae44cbaaae25c99a11ec3e](all-thermografische-gebouwanalyse.jsonld#L4847), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'dmv' in sentence 'Beschrijft deze kenmerken dmv punten, lijnen, polygonen en coördinaten.' for subject: [urn:oslo-toolchain:78ae94c9c21b55e255ed89d21a665809121217c669a393230a8034d0d2d1fc98](all-thermografische-gebouwanalyse.jsonld#L7595), replace with 'door middel van'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv als attribuut ve persoon of gebouw... De adresvoorstelling heeft niet enkel betrekking op Belgische adressen, ze kan gebruikt worden om buitenlandse adressen weer te geven (waar mogelijk andere adresaanduidingen dan huisnummer of busnummer worden gebruikt of waar adrescomponenten zoals adresgebieden voorkomen).' for subject: [urn:oslo-toolchain:d3e83e44ee1aa97f14f0d81d29b656ebeb87061f675af953966cdf11588f71fa](all-thermografische-gebouwanalyse.jsonld#L7643), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 've' in sentence 'Bv als attribuut ve persoon of gebouw... De adresvoorstelling heeft niet enkel betrekking op Belgische adressen, ze kan gebruikt worden om buitenlandse adressen weer te geven (waar mogelijk andere adresaanduidingen dan huisnummer of busnummer worden gebruikt of waar adrescomponenten zoals adresgebieden voorkomen).' for subject: [urn:oslo-toolchain:d3e83e44ee1aa97f14f0d81d29b656ebeb87061f675af953966cdf11588f71fa](all-thermografische-gebouwanalyse.jsonld#L7643), replace with 'van een'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'In essentie een waarde en de naam vh type van de waarde. In deze context gaat het over zaken zoals operator, omgevingstemperatuur etc.' for subject: [urn:oslo-toolchain:6cd3bea3448f83a4dd125d0ebf23a25ab24a93a525affadadc68456ccc163fc3](all-thermografische-gebouwanalyse.jsonld#L7685), replace with 'van het'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found sentence without a '.': 'In de context van gebouwen heeft dit betrekking op energetische eigenschappen, typisch voor een specifiek pand' for subject: [urn:oslo-toolchain:ddddd9bbc1f8c8c371220dd2f80302c37a479dfb5cf2589d1ac2bc7baf793d0b](all-thermografische-gebouwanalyse.jsonld#L8110)

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'ttz' in sentence 'Sensoren genereren een resultaat op basis van een Stimulus, ttz een verandering in de omgeving, of op basis van resultaten van andere Observaties. Ze worden typisch gehost door een Platform. Voorbeelden zijn snelheidsmeters, gyroscopen, barometers, magnetometers gemonteerd op een smart phone. Ook bv het menselijk oog kan beschouwd worden als een Sensor.' for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194), replace with 'het is te zeggen'

2026-10-08T19:29:01.838Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Sensoren genereren een resultaat op basis van een Stimulus, ttz een verandering in de omgeving, of op basis van resultaten van andere Observaties. Ze worden typisch gehost door een Platform. Voorbeelden zijn snelheidsmeters, gyroscopen, barometers, magnetometers gemonteerd op een smart phone. Ook bv het menselijk oog kan beschouwd worden als een Sensor.' for subject: [[urn:oslo-toolchain:b942791082dbbba481b8d8fbb3bc376655b7367fce34871d1ee750f8c025c015](all-thermografische-gebouwanalyse.jsonld#L7840)](all-thermografische-gebouwanalyse.jsonld#L194), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Deze componenten kunnen Systemen op zich zijn. In deze context zijn het Systemen die een Observatieprocedure realiseren (typisch een Sensor) of waarmee een Bemonsteringsprocedure wordt uitgevoerd (bv een Boorinstallatie).' for subject: [urn:oslo-toolchain:39c408dc8d6a746c3a0ea674094d0c7c51911017ea6f079ede5a16f8253b19b3](all-thermografische-gebouwanalyse.jsonld#L561), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'ihkv' in sentence 'Relevant ihkv het Renovatieproject, bvb EPC-waarde, isolatiewaarde vh dak, vastgesteld of beschermd onroerend erfgoed etc' for subject: [urn:oslo-toolchain:4f73baa3053dec5de1f4cf9fce3f075072154858d793b5a8c39c2a04c1f60d1b](all-thermografische-gebouwanalyse.jsonld#L729), replace with 'in het kader van'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'bvb' in sentence 'Relevant ihkv het Renovatieproject, bvb EPC-waarde, isolatiewaarde vh dak, vastgesteld of beschermd onroerend erfgoed etc' for subject: [urn:oslo-toolchain:4f73baa3053dec5de1f4cf9fce3f075072154858d793b5a8c39c2a04c1f60d1b](all-thermografische-gebouwanalyse.jsonld#L729), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Relevant ihkv het Renovatieproject, bvb EPC-waarde, isolatiewaarde vh dak, vastgesteld of beschermd onroerend erfgoed etc' for subject: [urn:oslo-toolchain:4f73baa3053dec5de1f4cf9fce3f075072154858d793b5a8c39c2a04c1f60d1b](all-thermografische-gebouwanalyse.jsonld#L729), replace with 'van het'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv Meetbereik,Nauwkeurigheid,Resolutie etc.' for subject: [urn:oslo-toolchain:50391fddb04a006afc5abbff149112f9eed78ef95bd8e67b98f57f99428d5292](all-thermografische-gebouwanalyse.jsonld#L1382), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Slaat op zaken als Meetbereik, Nauwkeurigheid, Afwijking, Resolutie, Responstijd, etc. en de eventuele Condities waaronder die specificaties gelden, bv een Nauwkerigheid van 1mm is gegarandeerd voor afstanden onder de 100 meter.' for subject: [urn:oslo-toolchain:199891c289cfd023c5bc0e399b8e325967f0f232415c3b5a3a4dc9f190b535d2](all-thermografische-gebouwanalyse.jsonld#L1430), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'bv' in sentence 'Slaat op zaken als onderhoud of de vereiste netspanning en de eventuele bijkomende condities, bv om de 3 weken is onderhoud nodig (door een gespecialiseerde firma) of de spanning op het net voor de voeding vh Systeem moet tussen 110 en 230 Volt liggen (bij normaal verbruik).' for subject: [urn:oslo-toolchain:dc5e939857178933df81554e906638a1b5bfde28fd13b98472d6fc93a532cb63](all-thermografische-gebouwanalyse.jsonld#L1478), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Slaat op zaken als onderhoud of de vereiste netspanning en de eventuele bijkomende condities, bv om de 3 weken is onderhoud nodig (door een gespecialiseerde firma) of de spanning op het net voor de voeding vh Systeem moet tussen 110 en 230 Volt liggen (bij normaal verbruik).' for subject: [urn:oslo-toolchain:dc5e939857178933df81554e906638a1b5bfde28fd13b98472d6fc93a532cb63](all-thermografische-gebouwanalyse.jsonld#L1478), replace with 'van het'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv onderhoud of de netspanning.' for subject: [urn:oslo-toolchain:ba7d09141c3f9e2ee4e6ba487ca786b3fcdca6f746f95041a4ac642ecfcfa7c9](all-thermografische-gebouwanalyse.jsonld#L1526), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Slaat op de levensduur vh Systeem als geheel of van cruciale delen ervan zoals de batterij en de Condities waaronder die kenmerken gelden. Bv de batterij van het systeem gaat 3 weken mee alvorens ze opnieuw moet worden opgeladen op voorwaarde dat de temperatuur tussen -5 en +35 graden ligt.' for subject: [urn:oslo-toolchain:fda15210d99a1b7d03286cdde99e19652036ef1dbfa485549ac5b9728a1ad583](all-thermografische-gebouwanalyse.jsonld#L1574), replace with 'van het'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Slaat op de levensduur vh Systeem als geheel of van cruciale delen ervan zoals de batterij en de Condities waaronder die kenmerken gelden. Bv de batterij van het systeem gaat 3 weken mee alvorens ze opnieuw moet worden opgeladen op voorwaarde dat de temperatuur tussen -5 en +35 graden ligt.' for subject: [urn:oslo-toolchain:fda15210d99a1b7d03286cdde99e19652036ef1dbfa485549ac5b9728a1ad583](all-thermografische-gebouwanalyse.jsonld#L1574), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv de levensduur van de batterij.' for subject: [urn:oslo-toolchain:7ce3b8d7460aa141d0c0bc7f958dd1dd3c59c72e7d28eab16c39d75568622106](all-thermografische-gebouwanalyse.jsonld#L1622), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bv' in sentence 'Bv de opgegeven Nauwkeurigheid van een Sensor die de windsnelheid meet geldt enkel voor windsnelheden tussen 10 en 60 m/s.' for subject: [urn:oslo-toolchain:25863b4e03538ca46f3273a819ec94bba608041e9bf1ee40e15e7bbc1608de77](all-thermografische-gebouwanalyse.jsonld#L1805), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'vd' in sentence 'Type vd string slaat op het identificatiesysteem (incl de versie ervan), de string zelf op de eigenlijke identificator.' for subject: [urn:oslo-toolchain:bbd0b9cafd583f7cbc517c9e90b392ed5cb58b816344971f7a29c516a7842928](all-thermografische-gebouwanalyse.jsonld#L1855), replace with 'van de'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'incl' in sentence 'Type vd string slaat op het identificatiesysteem (incl de versie ervan), de string zelf op de eigenlijke identificator.' for subject: [urn:oslo-toolchain:bbd0b9cafd583f7cbc517c9e90b392ed5cb58b816344971f7a29c516a7842928](all-thermografische-gebouwanalyse.jsonld#L1855), replace with 'inclusief'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'tbv' in sentence 'Specialisatie van Adresvoorstelling:locatieaanduiding tbv Belgische adressen.' for subject: [urn:oslo-toolchain:cb122dd9bc3a0407b62a3cea067243a232d9db681d2c1de146b4994e2672ccc3](all-thermografische-gebouwanalyse.jsonld#L2801), replace with 'ten behoeve van'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'tbv' in sentence 'Specialisatie van Adresvoorstelling:locatieaanduiding tbv Belgische adressen.' for subject: [urn:oslo-toolchain:fbced3b6f179b8fd93f9635f297eae3c1f6a82d574df41c35685a47d7ccc2466](all-thermografische-gebouwanalyse.jsonld#L2866), replace with 'ten behoeve van'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bvb' in sentence 'Bvb de naam vh gehucht waarin het adres ligt.' for subject: [urn:oslo-toolchain:b47c8d694583794d904c41d2aae1cad8780e3292cc7546ed21ab56e108a7f844](all-thermografische-gebouwanalyse.jsonld#L2987), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'vh' in sentence 'Bvb de naam vh gehucht waarin het adres ligt.' for subject: [urn:oslo-toolchain:b47c8d694583794d904c41d2aae1cad8780e3292cc7546ed21ab56e108a7f844](all-thermografische-gebouwanalyse.jsonld#L2987), replace with 'van het'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'Bvb' in sentence 'Het datatype Resource is te substitueren door een toepasselijk datatype. Bvb voor een EPC-score een KwantiatieveWaarde met waarde in procent of een skos:Concept met een kwalitatieve waarde (A, B, C etc). Bvb voor onroerend erfgoed een skos:Concept met waarde VastgesteldOnroerendErfgoed of BeschermdOnroerenderfgoed.' for subject: [urn:oslo-toolchain:7d70bd0a4a196014a571c450656124dda5a50e7d11ae44cbaaae25c99a11ec3e](all-thermografische-gebouwanalyse.jsonld#L4847), replace with 'bijvoorbeeld'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found abbreviation 'dmv' in sentence 'Beschrijft deze kenmerken dmv punten, lijnen, polygonen en coördinaten.' for subject: [urn:oslo-toolchain:78ae94c9c21b55e255ed89d21a665809121217c669a393230a8034d0d2d1fc98](all-thermografische-gebouwanalyse.jsonld#L7595), replace with 'door middel van'

2026-10-08T19:29:01.839Z warn: [JsonLdValidationService]: Found sentence without a '.': 'In de context van gebouwen heeft dit betrekking op energetische eigenschappen, typisch voor een specifiek pand' for subject: [urn:oslo-toolchain:ddddd9bbc1f8c8c371220dd2f80302c37a479dfb5cf2589d1ac2bc7baf793d0b](all-thermografische-gebouwanalyse.jsonld#L8110)

2026-10-08T19:29:01.841Z warn: [JsonLdValidationService]: Labels must only contain alphabetical characters: 'BIM_Gebouw' for subject: [urn:oslo-toolchain:abb4b0e6ef8d096b8fb5ef18795462129d9a0b583355f36171d55e1dca66f2d8](all-thermografische-gebouwanalyse.jsonld#L1023)

2026-10-08T19:29:01.841Z warn: [JsonLdValidationService]: Labels must only contain alphabetical characters: 'BIM_Element' for subject: [urn:oslo-toolchain:32198f90e52bc4aaf21073d249362761dab0ed51f36dd220959220be2b4cf88f](all-thermografische-gebouwanalyse.jsonld#L1070)

2026-10-08T19:29:01.841Z warn: [JsonLdValidationService]: Labels must only contain alphabetical characters: 'BIM_Gebouw' for subject: [urn:oslo-toolchain:abb4b0e6ef8d096b8fb5ef18795462129d9a0b583355f36171d55e1dca66f2d8](all-thermografische-gebouwanalyse.jsonld#L1023)

2026-10-08T19:29:01.842Z warn: [JsonLdValidationService]: Labels must only contain alphabetical characters: 'BIM_Element' for subject: [urn:oslo-toolchain:32198f90e52bc4aaf21073d249362761dab0ed51f36dd220959220be2b4cf88f](all-thermografische-gebouwanalyse.jsonld#L1070)

2026-10-08T19:29:01.843Z error: [JsonLdValidationService]: Found missing class or attribute (Toestel): [urn:oslo-toolchain:005f9528c72fe38c8c6ea516c64b0eda6eba1db9b42515152f9fadd19d8aa0c3](all-thermografische-gebouwanalyse.jsonld#L7829) in Application Profile

2026-10-08T19:29:01.843Z error: [JsonLdValidationService]: Found missing class or attribute (Platform): [urn:oslo-toolchain:23a58ad8b235a857a57704dbcc3c0cd5c747cb2cd22676d275df8932f7342f91](all-thermografische-gebouwanalyse.jsonld#L7852) in Application Profile

2026-10-08T19:29:01.844Z error: [JsonLdValidationService]: Found missing class or attribute (Informatieobject): [urn:oslo-toolchain:addceca7e2b26c4bb64465b579fa9f5655f23bd84c856213c42a502d4fcc29c4](all-thermografische-gebouwanalyse.jsonld#L7980) in Application Profile

2026-10-08T19:29:01.850Z info: [JsonLdValidationService]: Validation found 10 non-whitelisted assigned URIs

2026-10-08T19:29:01.850Z info: [JsonLdValidationService]: Validation found 104 sentences with spelling mistakes or abbreviations.

2026-10-08T19:29:01.850Z info: [JsonLdValidationService]: Validation found 4 labels with spelling mistakes or abbreviations.

2026-10-08T19:29:01.850Z info: [JsonLdValidationService]: Validation successful! All base URIs seem to be valid.

2026-10-08T19:29:01.850Z info: [JsonLdValidationService]: Validation found 3 missing referenced classes or attributes.

#||# command: node /app/report_lines_links.js -i /tmp/workspace/report4/doc/applicatieprofiel/thermografische-gebouwanalyse/kandidaatstandaard/2025-05-22/all-thermografische-gebouwanalyse.jsonld -o /tmp/reportlines  


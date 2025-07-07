#||#  oslo-stakeholders-converter

#||# -------------------------------------

node ./bin/runner.js [args]



Options:

      --version             Show version number                        [boolean]

      --input               URL or local path to an OSLO stakeholders csv file.

                                                                      [required]

      --output              Name of the output file

                                                [default: "stakeholders.jsonld"]

      --contributorsColumn  Name of the contributors column.

                                                          [default: "MijnKolom"]

      --silent              All logs are suppressed   [boolean] [default: false]

      --logLevel            Log only if level is less than or equal to this

                            level

       [choices: "error", "warn", "info", "verbose", "debug", "silly"] [default:

                                                                         "info"]

      --outputFormat        Define the output format

                  [choices: "application/ld+json", "application/json"] [default:

                                                          "application/ld+json"]

      --iri                 IRI of the specification of which these stakeholders

                            are part of.

  -h, --help                Show help                                  [boolean]



Argument check failed: (args) => {

            if (args.outputFormat === core_1.OutputFormat.JsonLd) {

                throw new Error(`--iri is required when outputFormat is ${core_1.OutputFormat.JsonLd}}`);

            }

        }


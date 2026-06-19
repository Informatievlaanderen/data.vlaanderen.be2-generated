#||# oslo-jsonld-validator   

#||# -------------------------------------  

node ./bin/runner.js [args]



Options:

      --version                 Show version number                    [boolean]

      --input                   Local path or URL to JSON-LD file to validate.

                                                                      [required]

      --publicationEnvironment  The base URI of environment where the document

                                will be published.                    [required]

      --specificationType       Type of the document.

                                   [choices: "ApplicationProfile", "Vocabulary"]

      --whitelist               Local path or URL to whitelist file (JSON array

                                of URI prefixes).                     [required]

  -h, --help                    Show help                              [boolean]



Missing required argument: publicationEnvironment


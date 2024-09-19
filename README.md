# Kenya 2010 Constitution

This repo has a [machine-readable version][0] of the Kenya 2010
Constitution's articles in the JSON format.

[0]: json/ConstitutionKenya2010.json

The text was extracted from the pdf version of the 2010 constitution
found at the [Kenya Law website][1], last revised in 2022.

[1]: https://kenyalaw.org/kl/fileadmin/pdfdownloads/TheConstitutionOfKenya.pdf

A version of the PDF version is [included][2].

[2]: pdf/TheConstitutionOfKenya.pdf

The process used to produce the JSON version from the PDF version is
documented in an accompanying [notebook][3].

[3]: produce_json_from_pdf.ipynb

## Data Dictionary

| Field      | Description                                                                                                                    |
|------------|--------------------------------------------------------------------------------------------------------------------------------|
| number     | the article's number                                                                                                           |
| title      | the article's title                                                                                                            |
| lines      | a list of lines that consist the clauses of the article                                                                        |
| chapter    | a list with the chapter number and title the article belongs to                                                                |
| part       | if the chapter is divided into parts, this is the list with part number and title the article belongs to, otherwise it is null |

## License

Public Domain

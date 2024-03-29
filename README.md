# Chronometric Age Extension

The Chronometric Age extension is a vocabulary maintained by the [Darwin Core Maintenance Interest Group](https://www.tdwg.org/standards/dwc/#maintenance%20group). It includes a glossary of terms (in other contexts these might be called properties, elements, fields, columns, attributes, or concepts) intended to **facilitate the sharing of information about chronometric ages and the techniques used to determine them** by providing identifiers, labels, and definitions.

## Getting started

[Chronometric Age Extension Quick Reference Guide](https://tdwg.github.io/chrono/terms/)
<!-- [Chronometric Age Extension Quick Reference Guide](https://chrono.tdwg.org/terms/) -->

Documents:

- [List of terms document](https://tdwg.github.io/chrono/list/): Comprehensive metadata for current and obsolete terms in human readable form
<!-- - [List of terms document](https://chrono.tdwg.org/list/): Comprehensive metadata for current and obsolete terms in human readable form -->
- [Complete term history table](vocabulary/term_versions.csv): A CSV file with the full version history of Chronometric Age terms
- [Utility documents](dist/): CSV files of vertical and horizontal term lists plus the Darwin Core Extension schema
- [Website documents](docs/): Markdown files that form the source for the [Chronometric Age Extension website](https://tdwg.github.io/chrono)
- [Feature Report](reports/Feature%20Report.md): Document identify the features that should be included in the enhancement in order to achieve identified goals
- [Implementation Experience Report](reports/Implementation%20Experience%20Report.md): Documentation of the experience of independent implementations with the features listed in the Feature Report
<!-- - [Website documents](docs/): Markdown files that form the source for the [Chronometric Age Extension website](https://chrono.tdwg.org/) -->

Community:

- [How to contribute](.github/CONTRIBUTING.md): a guide on how to contribute to the Chronometric Age Extension

## Repo structure

The repository structure is described below. Files/directories indicated with `GENERATED` should not be edited manually.

```
├── .github
│   └── CONTRIBUTING.md       : Guide on how to contribute
│
├── build
│   ├── README.md                 : Workflow for generating a new version of the vocabulary
│   ├── build-termlist.ipynb      : Juyter notebook to construct the term list
│   ├── build.py                  : Build script to generate distribution files from the normative document
│   ├── generate_term_versions.py : Script to build the terms_versions.csv file
│   ├── qrg-list.csv              : List of the term IRIs in the order that they are to appear in the Quick Reference Guide
│   ├── requirements.txt          : List of libraries required by the build scripts
│   ├── termlist-footer.md        : Footer to append to the generated term list document
│   ├── termlist-header.md        : Header to prepend to the generated term list document
│   └── terms.tmpl                : A Jinja2 template to generate the Quick Reference Guide
│
├── dist                               : GENERATED Distribution files generated by build.py
│   ├── ChronometricAge_yyyy-mm-dd.xml : GENERATED XML files for the versions of Chronometric Age Extension needed by IPT
│   ├── simple_chrono_horizontal.csv   : GENERATED CSV file with Chronometric Age terms as a row
│   └── simple_chrono_vertical.csv     : GENERATED CSV file with Chronometric Age terms as a column
│
├── docs
│   └── terms
│   │   └── index.md      : GENERATED Content for Quick Reference Guide generation using Jekyll
│   ├── _config.yml       : Jekyll site configuration for Quick Reference Guide
│   ├── list
│   │   └── index.md      : Content for Term list document generation using Jekyll
│   └── index.md          : Header for Quick Reference Guide generation using Jekyll
│
├── vocabulary
│   └── term_versions.csv : Chronometric Age term versions, contains the complete history of the terms
│
├── .gitignore            : Files and directories to be ignored by git
├── LICENSE               : Repository license
└── README.md             : Description of this repository
```

## Contributors

[List of contributors](https://github.com/tdwg/chrono/contributors)

## License

[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)

## Recommended citation

For the Chronomtric Age Extension in general, consider the peer-reviewed article:

> Brenskelle L, Davis E, Wieczorek J, Lefebvre M, Wallis N, Emery K, Guralnick R (in prep) It’s Time For Better Reporting of Absolute Age In Species Occurrence Databases.

For this repository:

> Darwin Core Maintenance Interest Group, Biodiversity Information Standards (TDWG) (2020). Chronometric Age Extension. Zenodo. https://doi.org/x

The citation above represents all versions of the repository. Specific [versions/releases](https://github.com/tdwg/chrono/releases) from 2018 onwards are also deposited on Zenodo.

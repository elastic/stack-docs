# stack-docs

This repository is the home for the cross-stack (Elastic Stack) documentation, such as the Installation and Configuration Guide and the Machine Learning Guide.

## Directories

Within this repo, the `/docs/en/` directory is structured as follows:

| Directory             | Description |
| --------------------- | ----------- |
| __getting-started__ | Contains the source files for the [Getting Started Guide](https://www.elastic.co/guide/en/elastic-stack-get-started/current/index.html).|
| __gke-on-prem__      | Contains the source files for [Elastic Stack and Google Cloud's Anthos](https://www.elastic.co/guide/en/integrations-developer/current/index.html)
| __glossary__     | Contains the source files for the [Elastic Glossary](https://www.elastic.co/guide/en/elastic-stack-glossary/current/index.html).|
| __install-upgrade__ | Contains the source files for the [Elastic Installation and Upgrade Guide](https://www.elastic.co/guide/en/elastic-stack/current/index.html).|
| __stack/ml__ | Contains the source files for the [Machine Learning Guide](https://www.elastic.co/guide/en/machine-learning/current/index.html).|

## Build

To build the docs:

1. Identify which book you want to build and whether it has any dependencies on other repositories.
You can see the required repositories for each book in either the [conf.yaml](https://github.com/elastic/docs/blob/master/conf.yaml) or the [doc_build_aliases.sh file](https://github.com/elastic/docs/blob/master/doc_build_aliases.sh).

2. Check out the `elastic/docs` repository and any other necessary repositories.

3. Run the appropriate `build_docs` script, as listed in the [doc_build_aliases.sh file](https://github.com/elastic/docs/blob/master/doc_build_aliases.sh).


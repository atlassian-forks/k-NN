# CHANGELOG
All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html). See the [CONTRIBUTING guide](./CONTRIBUTING.md#Changelog) for instructions on how to add changelog entries.

## [Unreleased 3.0](https://github.com/opensearch-project/k-NN/compare/2.x...HEAD)
### Features
### Enhancements
### Bug Fixes 
### Infrastructure
### Documentation
### Maintenance
### Refactoring

## [Unreleased 2.x](https://github.com/opensearch-project/k-NN/compare/2.16...2.x)
### Features
### Enhancements
* Add functionality to iteratively insert vectors into a faiss index to improve the memory footprint during indexing. [#1840](https://github.com/opensearch-project/k-NN/pull/1840)
### Bug Fixes
* Corrected search logic for scenario with non-existent fields in filter [#1874](https://github.com/opensearch-project/k-NN/pull/1874)
* Fixed and abstracted functionality for allocating index memory [#1933](https://github.com/opensearch-project/k-NN/pull/1933)
### Infrastructure
### Documentation
### Maintenance
### Refactoring
* Clean up parsing for query [#1824](https://github.com/opensearch-project/k-NN/pull/1824)

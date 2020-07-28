# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [0.0.6] - 2020-07-27
### Removed
- tern-skos:hasCategoricalVariableCollection rdfs:subPropertyOf skos:relatedMatch
### Added
- tern-skos:equipment
- tern-skos:procedure
- tern-skos:reasonForCollection


## [0.0.5] - 2020-04-20
### Changed
- tern-skos:hasVariable to tern-skos:hasParameter


## [0.0.4] - 2020-04-08
### Removed
- tern-skos:hasQuantitativeVariable
### Added
- tern-skos:hasCategoricalVariableCollection


## [0.0.3] - 2020-04-06
### Removed
- domain and range for:
    - tern-skos:globalMatch
    - tern-skos:isGlobalMatchOf
    - tern-skos:hasMethod
    - tern-skos:hasVariable
    - tern-skos:hasQuantitativeVariable
    - tern-skos:hasObservationTheme


## [0.0.2] - 2020-02-27
### Added
- sosa:ObservableProperty with subclass to skos:Concept
- sosa:Procedure with subclass to skos:Concept
- tern-ssn:QuantitativeVariable with subclass to skos:Concept
- domain and range for:
    - tern-skos:globalMatch
    - tern-skos:isGlobalMatchOf
    - tern-skos:hasMethod
    - tern-skos:hasVariable
    - tern-skos:hasQuantitativeVariable
    - tern-skos:hasObservationTheme
### Changed
- tern-skos:hasCategoricalVariable changed to tern-skos:hasQuantitativeVariable
- tern-skos:hasObservationGroup changed to tern-skos:hasObservationTheme
### Removed
- Now defined in tern-ssn instead of tern-skos
    - tern-ssn:Variable
    - tern-ssn:Method
    - tern-ssn:CategoricalVariable


## [0.0.1] - 2020-02-26
### Added
- Initial release.
- tern-skos:globalMatch
- tern-skos:hasCategoricalVariable
- tern-skos:hasMethod
- tern-skos:hasObservationGroup
- tern-skos:hasVariable
- tern-skos:isGlobalMatchOf
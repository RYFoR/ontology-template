# Usage

To use this ontology, follow these steps:

1. Download or clone this repository.
2. Import `ontology.owl` or `ontology.rdf` into your ontology editor or application.
3. Start using the defined classes and properties in your ontology modeling or data.

## Example Data

The main directory contains a sample data file (`example.ttl`) that demonstrates how to represent a person with a name.

```turtle
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix ex: <http://example.org/ontology#> .

ex:JohnDoe a ex:Person ;
    ex:hasName "John Doe" .
```
# owl-qa
An OWL-based QA tool using a post-coordination approach

## Case study of CDEs from two TCGA cancer genome study domains
OWL rendering of CDEs in the domain Clinical Pharmaceutical

https://github.com/caCDE-QA/owl-qa/blob/master/dec-ontology-01.ttl

https://github.com/caCDE-QA/owl-qa/blob/master/dec-ontology-01-with-NCIt.ttl (with owl:imports)

OWL rendering of CDEs in the domain Clinical Shared

https://github.com/caCDE-QA/owl-qa/blob/master/dec-ontology-02.ttl

https://github.com/caCDE-QA/owl-qa/blob/master/dec-ontology-02-with-NCIt.ttl (with owl:imports)

To detect modeling errors, 

1) load one of the OWL files into a Protege 5 Ontology Editing environment (http://protege.stanford.edu/) and ;

2) invoke the reasoning services from a DL-based resoner (eg., HermIT)


## XML2RDF Transformation Examples
The caDSR CDEs and TCGA data dictionary were converted from XML into RDF using the XML2RDF tool that was developed for the Redefer project. The original XML files and transformed RDF files can be found at the following link.
* https://github.com/gqjiang/cimi2rdf

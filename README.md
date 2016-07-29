# owl-qa
An OWL-based QA tool using a post-coordination approach

## System Architecture

![alt tag](https://github.com/caCDE-QA/owl-qa/blob/master/system-architecture.jpg)

## Publications
* Jiang G, Solbrig HR, Prud'hommeaux E, Tao C, Weng C, Chute CG. Quality Assurance of Cancer Study Common Data Elements Using A Post-Coordination Approach. AMIA Annu Symp Proc. 2015 Nov 5;2015:659-68. eCollection 2015. http://www.ncbi.nlm.nih.gov/pubmed/26958201



## Case study of CDEs from two TCGA cancer genome study domains
OWL rendering of CDEs in the domain Clinical Pharmaceutical

https://github.com/caCDE-QA/owl-qa/blob/master/dec-ontology-01.ttl

https://github.com/caCDE-QA/owl-qa/blob/master/dec-ontology-01-with-NCIt.ttl (with owl:imports)

OWL rendering of CDEs in the domain Clinical Shared

https://github.com/caCDE-QA/owl-qa/blob/master/dec-ontology-02.ttl

https://github.com/caCDE-QA/owl-qa/blob/master/dec-ontology-02-with-NCIt.ttl (with owl:imports)

To detect modeling errors, 

1) load one of the OWL files into an Protege 5 Ontology Editing environment (http://protege.stanford.edu/) and ;

2) invoke the reasoning services from a DL-based resoner (eg., HermIT)


## XML2RDF Transformation Examples
The caDSR CDEs and TCGA data dictionary were converted from XML into RDF using the XML2RDF tool that was developed for the Redefer project. The original XML files and transformed RDF files can be found at the following link.
* https://github.com/gqjiang/cimi2rdf

# Data-Semantics-Assignments

## Assignment 1
Submit and query DBpedia Endpoint on http://dbpedia.org/sparql

Query DBpedia to find more information about your favorite actor / actress. (As actors may have been described using different properties and not all the queries below might have an answer for your favorite actor, please feel free to substitute a query with any query you are curious about. E.g., there might be no information in DBpedia to answer to query number 4 about the duration of the last film. You can substitute such query with another of your choice. For example: How old is your actor / actress ‘partner? Or How old is his / her older child?)

1. Is your favorite actor / actress / married?
2. How many films did he / she starred in?
3. Which is the last film he /she performed and when?
4. Which is the duration of the last film he / she starred?
5. Give me the total number of actors that performed in the latest film of your favorite actor.

Provided that you satisfy the above queries, you can create the RDF graph considering the results obtained from the above questions. You can create only one RDF graph, which will contain all the results of the above queries. So, in the same graph, you have to represent the answer of the queries for his / her age, films, the year of the latest film, the budget and the female actress in the last film he starred in. Consider it as the complete RDF graph that you should query in order to answer to the above questions. The scope of this part of the assignment is to evaluate your ability to draw an RDF graph (complying with the RDF graph symbolic).

## Assignment 2
Modify the companies-geo.rdfs-owl-L2-2.owl ontology with Protégé by creating two ontologies as specified below.

#### 1. companies-geo.rdfs-owl-L2-2-Your_Surname_clean.owl
These specifications must be satisfied in ensemble in the final ontology; the order in which they are listed here below does not need to reflect the optimal order for a sequential implementation.

* Add two more branches to the ontology (the new classes are highlighted in bold): 
  - Person > Student
  - Organization > University
* Make sure that each new class has at least two instances; you must appear as an
instance of Student
* Model the following patterns by specifying the required object and datatype properties and by introducing two triples for each the pattern:
  - Persons are friends to each other 
  - Persons have a birthplace
  - Persons have names
  - Students attends universities
  - Universities have addresses
* Interpret the above patterns by specifying domain and range restrictions over object
and datatype properties so as to implement intuitively sound inferences in the ontology
* Use a reasoner to make sure that there are at least two examples of desired inferences, based on your axiomatization
Provided that you satisfy the above specifications, you can make any additional change to the ontology needed to improve your ontology.

#### 2. companies-geo.rdfs-owl-L2-2-Your_Surname_wrong.owl
Modify the companies-geo.rdfs-owl-L2-2-Your_Surname_clean.owl ontology in such a way that either an inconsistency is derived or an unintended (or, counterintuitive, or unde- sirable) inference is drawn.

## Assignment 3
Create and execute a pipeline in SILK to generate sameAs links between Google Adwords and a country of your choice (from Geonames).

Create and execute to the best of your knowledge a pipeline using the SILK framework to generate sameAs links between Google Adwords (https://developers.google.com/adwords/api/docs/appendix/geo/geotargets-2020-03-03.csv) and the country of your choice from Geonames.

Before starting, please refer to the list of the countries in this link (https://docs.google.com/spreadsheets/d/1UKQbgpwOpBbV7Nuc_mKf6a_fUpkHElKnOCrcMulraZg/edit?usp=sharing) to choose the country for which you want to generate links.

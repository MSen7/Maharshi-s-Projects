
In the B2B _B2C_Ontology.ttl, we define an ideal B2B and B2C scenario using primarily RDF, RDFS and OWL ontologies. 

We define a large number of classes(such as customer, competitor, seller etc.), MarketObject types( product and application in our case), the stages the MarketObjects are in(Production, Testing, Research) etc, some examples of products and applications (Robotics, Warehousing, Delivery Service), and their respective subclasses( for example, “autonomous_delivery_device” is a further subclass under Delivery Service). 
We also define a large number of individual objects in this context( for example, "Expanding and Modernizing a Warehouse" for the product “Building”). It can be noted at this point, that we use OWL term owl:sameAs very frequently for the individuals. Then, we define a number of properties, (such as delivers, installs, improves, expands) and use owl:SymmetricProperty for one of them. Finally, we show some examples of classes(all of which are subclasses of the Organization class) and the relations between them.

Hydrogen_Refined_Graph.ttl is a knowledge graph about the Hydrogen industry.

'An Iterative Approach to finding pearson coefficient' is a method I developed, using Cypher queries, to find pearson coefficients between all pairs of parameters having numerical value in a graph, without knowledge of either the parameter name or the paths between the parameters.

'An Introduction to SHACL' is a documentation on SHACL and its usage.

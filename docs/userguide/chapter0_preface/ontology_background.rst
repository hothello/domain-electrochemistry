Background
----------

The roots of modern ontologies trace back to ancient Greece. Ontology, as a branch of metaphysics, deals with the nature of being. These philosophical origins are still evident in the way we conceptualize and structure knowledge in modern ontologies. You can explore more about the philosophical aspects of ontology here. 

In information science, ontologies were reinvented in the mid-20th century to bridge the gap between how humans and computers process information. For humans, information is understood as a set of concepts with meaningful, logically consistent relationships. For computers, however, information is represented as binary code: a sequence of ones and zeros.

.. admonition:: Thought Experiment: The Robot at the Salad Bar

   Imagine you have built a robot to do your bidding. You ask it to go to a restaurant, make a salad at the salad bar, and bring it back to you. What information does the robot need to know to accomplish that task?

   It needs to know...

   - where the restaurant is and how to get there
   - the recipe for a salad and how to select the ingredients from the salad bar
   - that a salad comes in a bowl and is proportioned as a meal for one or more people
   - etc.

   Even this seemingly simple task requires a vast amount of information across multiple domains. However, the challenge isn’t just the volume of information—it’s also the need for this information to be linked together in a logically consistent way. This linkage allows the robot to reason about aspects of the task that are not explicitly stated.

To get over this barrier, researchers developed ontologies in the form of network graphs. These graphs link concepts using relationships in node-edge-node statements called *triples*. The concepts within the graph can then be mapped to computer datasets, effectively assigning meaning to the data and enabling machines to process and reason about it.

The next major step came in 1989 from a quiet corner of Switzerland. A 34-year-old researcher at CERN named Tim Berners-Lee was trying to develop a way to manage the vast amount of data generated by the nuclear research facility. He proposed a knowledge management system using hypertext to link documents and datasets. He called this system *The Mesh*, but within a few short years, it would be known by another name: *The World Wide Web*.

After the invention of the World Wide Web, the volume of information available to humans and computers grew exponentially. It quickly became evident that merely linking resources with hypertext was not sufficient to navigate the wilderness of data. The answer was *The Semantic Web*, an extension of the World Wide Web that uses ontologies and other semantic tools to describe the meaning of data and the nature of its connections. 

To build the Semantic Web, the World Wide Web Consortium (W3C) created a core technology stack expressed as a system of standards, including the Resource Description Framework (RDF) and the Web Ontology Language (OWL). RDF provides a basic model for representing data as triples (subject-predicate-object) in a graph structure. OWL extends RDF and is designed to represent rich and complex knowledge about things, groups of things, and relationships between them. These Semantic Web standards - among others - are the foundation of much of today’s ontology development.

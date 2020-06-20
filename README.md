# NLP Summer Project
Introducing Inter-Relatedness between Wikipedia Articles in Explicit Semantic Analysis

## Abstract
Explicit Semantic Analysis (ESA) is a technique used to represent a piece of text as a vector in the space of concepts, such as Articles
found in Wikipedia. We propose a methodology to incorporate knowledge of Inter-relatedness between Wikipedia Articles to the vectors obtained from ESA using a technique called Retrofitting to improve the performance of subsequent tasks that use ESA to form vector embeddings. Especially we use an undirected Graph to represent this knowledge with nodes as Articles and edges as inter relations between two Articles. Here, we also emphasize how the ESA step could be seen as a predominantly bottom-up approach using a corpus to come up with vector representations and the incorporation of top-down knowledge which is the relations between Articles to further improve it. We test our hypothesis on several smaller subsets of the Wikipedia corpus and show that our proposed methodology leads to decent improvements in performance measures including Spearman's Rank correlation coefficient in most cases.

-Refer Final_Report for complete detail. 

## Reference
- Complete set of references are enlisted in project Report.

- @InProceedings{faruqui:2015:NAACL,
  author    = {Faruqui, Manaal and Dodge, Jesse and Jauhar, Sujay K.  and  Dyer, Chris and Hovy, Eduard and Smith, Noah A.},
  title     = {Retrofitting Word Vectors to Semantic Lexicons},
  booktitle = {Proceedings of NAACL},
  year      = {2015},
 }

# Datasets and evaluation scripts for SeMantic Answer Type and Relation Prediction Task ([SMART 2022](https://smart-task.github.io/2022/))

Question Answering is a popular task in the field of Natural Language Processing and Information Retrieval, in which, the goal is to answer a natural language question (going beyond the document retrieval). Question or answer type classification and relation prediction plays a key role in question answering. The questions can be generally classified based on Wh-terms (Who, What, When, Where, Which, Whom, Whose, Why). A granular answer type classification is possible with popular Semantic Web ontologies such as DBpedia (~760 classes) and Wikidata (~50K classes). On the other hand, relation prediction for question is a hard task, some relations are semantically far and sometimes tokens deciding the relations are spread across the question, some relations are implicit in text, and there are lexical gaps in relation surface forms and KG property labels.

Thus, in the second iteration of SMART challenge, we have two independent tasks:

## Task 1 - Answer Type Prediction
Given a question in natural language, the task is to predict type of the answer using a set of candidates from a target ontology.

Datasets: 
- [SMART2022-AT-dbpedia](https://github.com/smart-task/smart-2022-datasets/tree/main/AT_answer_type_prediction/dbpedia)
- [SMART2022-AT-wikidata](https://github.com/smart-task/smart-2022-datasets/tree/main/AT_answer_type_prediction/wikidata)



## Task 2 - Relation Linking
Given a question in natural language, the task is to predict relation to used for identifying the correct answer.

Datasets: 
- [SMART2022-RL-dbpedia](https://github.com/smart-task/smart-2022-datasets/tree/main/RL_relation_linking/dbpedia)
- [SMART2022-RL-wikidata](https://github.com/smart-task/smart-2022-datasets/tree/main/RL_relation_linking/wikidata)

## Task 3 - Entity Linking
Given a question in natural language, the task is to identify the entities and link them to the KG for formulating the correct query to get the answer from the KB.

Datasets: 
- [SMART2022-EL-dbpedia](https://github.com/smart-task/smart-2022-datasets/tree/main/EL_entity_linking/dbpedia)
- [SMART2022-EL-wikidata](https://github.com/smart-task/smart-2022-datasets/tree/main/EL_entity_linking/wikidata)


## Project Description 
A Big Data search engine designed to rank academic articles based on query-title similarity and citation-based importance. The engine mimics Google Scholar's ranking mechanism by combining string similarity with PageRank computed from citation graphs using a custom MapReduce implementation in PySpark.

## Key Features
- Query-based search using keyword similarity in article titles
- Importance ranking using PageRank (implemented from scratch)
- Weighted aggreagtion for scoring the results based no the text similarity and importance score
- Graph-based modeling using citations as directed edges
- Big Data of [Citation dataset](https://www.kaggle.com/datasets/mathurinache/citation-network-dataset)- 12GB 
- Implemented based on Map-Reduce paradigm on PySpark

## Results 
Refer to the [presentation file](https://github.com/mehrdadhz-77/article_search_engine/blob/main/presentation_files.pdf) for more details and results achieved in the project. 






# Search-Engine
In this project, we implemented some searching algorithms to movies on based on search queries. 

## Feature and Technologies

1. Semantic Search using Qdrant:
   At the heart of the Movie Recommendation App lies a cutting-edge semantic search algorithm, leveraging the prowess of the Qdrant pretrained search model. This model is instrumental in transforming movie descriptions into intricate high-dimensional vectors, which encapsulate the very essence of their semantics. The power of Qdrant's search capabilities shines through as it effortlessly identifies movies that resonate closely with the user's preferences. This translates into a remarkably refined recommendation system, where users receive suggestions that truly align with their tastes and preferences, all made possible by the innovative Qdrant pretrained search model.

2. BERT for Contextual Understanding:
   BERT (Bidirectional Encoder Representations from Transformers) serves as a cornerstone in modern Natural Language Processing. This revolutionary model, powered by Transformers architecture, has redefined contextual understanding in text. By employing BERT for search tasks, the Movie Recommendation App leverages its bidirectional nature. BERT processes text in both directions, capturing intricate relationships between words and their context. This unique ability enables BERT to generate contextual embeddings for movie descriptions. Each word's representation is contextualized with respect to its entire sentence, ensuring a nuanced understanding of the text's meaning. When used in search, BERT-encoded descriptions become powerful representations, allowing the app to grasp subtle nuances and user intents, leading to more accurate and relevant recommendations.

3. Keyword Search using BM25:
   In information retrieval, BM25 (Best Matching 25) has emerged as a widely used ranking function. This algorithm tackles the challenge of relevance in keyword-based searches. BM25's approach centers on two crucial factors: keyword frequency and document length. The Movie Recommendation App harnesses the BM25 algorithm to enhance keyword-based movie searches. When a user inputs a query, BM25 evaluates the frequency of query terms within movie descriptions and adjusts for document length. This process results in a relevance score that highlights the movies with the closest alignment to the user's query. The BM25-powered keyword search mechanism ensures that the app identifies movies whose descriptions contain significant matches to the user's input, facilitating accurate and tailored recommendations.

## Acknowledgements

 - Sentence-Transformer : (https://pypi.org/project/sentence-transformers/) The Sentence Transformer library for encoding movie data into vectors.
 - Transformers : (https://pypi.org/project/transformers/2.1.0/) The Transformer library for using trained models.
 - rank-bm25 : (https://pypi.org/project/rank-bm25/) For tokenize and performing Search.

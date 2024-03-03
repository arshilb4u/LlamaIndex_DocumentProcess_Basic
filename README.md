# LlamaIndex_DocumentProcess_Basic
In this we have used document vector creation and retrieval from LlamaIndex also we can query the question with the help of same. Also we can use retriever and query Engine separately also

# used libraries
VectorStoreIndex -> convert document to vectors Embeddings
SimpleDirectoryReader-> Red directory containing PDF
StorageContext-> Store the vector embeddings for future use
load_index_from_storage-> load the vector embeddings
VectorIndexRetriever-> Retrieve the vector embed, this will help to retrieve the specified top k matched index from documents
SimilarityPostprocessor-> Help to retrieve the matching index with threshold


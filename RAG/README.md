

* Coursera Lab on setting up data for RAG. Specifically, we convert a csv file full of wine names, locations, and notes into a json-like format so we can then create embeddings from each row of our table. 

* Then, we perform the embedding with qdrant. We verify embeddings are created correctly with a test prompt.

* Finally, we integrate this information with a local LLM. This uses the data we queried in a cleaner response. We tell the model to fufil the role of helping the user select a wine. 

Link to Jupyter Notebook hosted on Coursera lab servers
[https://sharedghbzuoxg.labs.coursera.org/notebooks/learn-retrieval-augmented-generation/examples/1-managing-data/example.ipynb](url)

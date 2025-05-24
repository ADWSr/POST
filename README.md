# POST
POST is a knowledge graph embedding model that uses spatial analysis and inference to embed data into vector spaces.

* Model details -  POST is a knowledge graph embedding model that uses spatial analysis and inference to embed data 
into vector spaces. POST is trained on large amounts of location data, known facts, from which other known facts can 
be learned. POST using geoenrichment techniques to perform the spatial and inference analysis. The test model was 
trained on 17.9 million locations. POST models are Retrieval-Augmented Generation (RAG) pipelines that enhance the accuracy and reliability of language models by incorporating external knowledge. POST models are a key component in Agentic RAG AI systems: retrieval system (RAG), generation model (LLM), and agent layer.
* Intended uses -  POST is intended to be used for grounding Gen AI models with authoritative GIS data sources that 
tether the AI outputs to real-world data and contexts. POST reduces hallucinations and bias, enhances accuracy, and 
improves contextual awareness by using facts based in the real-world thereby giving the AI an internal world model, 
which they lack natively. 
* Limitations - While POST is well trained in spatial analysis and inference, it is only as good as the data it is 
trained on so it is critically important to have humans review POST output to ensure data quality and accurate 
interpretation of its results. The POST knowledge graph embedding model does not have the capability to 
independently search the web or any internal databases not provided to it during its training. The model can still 
hallucinate if not provided data that has not been validated, cleaned, and aggregated.
* Training data - The current test training data used for POST comes from only publicly available data sources. POST 
can be securely trained on corporate GIS databases.
* Evaluation - POST was tested on standard spatial relationships to validate the quality of its inference and ability 
to answer questions. Early alpha testers will soon have access to evaluate POST using unstructured testing. Upon 
completion of early alpha testing, an early-access closed beta will begin.

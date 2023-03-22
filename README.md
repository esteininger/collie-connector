# CollieConnector Framework Walkthrough

The CollieConnector framework consists of the following steps:

1. **Accept corpus**: Process the input data source for the generative model.
2. **Split into chunks**: Segment the input data into coherent and meaningful chunks.
3. **Embed the chunks**: Generate embeddings for the chunks and store them in a vector search engine.
4. **Ask a question (Q)**: Input a question or prompt for the generative model to address.
5. **Return top K chunks**: Retrieve the top K chunks most relevant to the question.
6. **Run chunks through GPT**: Feed the selected chunks into a GPT-based generative model to generate a response.
7. **Return results in structured form**: Return the generated response with embedded inline citations from the source of truth.

## Components

- **Pinecone**: Vector search engine used for embedding storage and retrieval.
- **OpenAI**: Provides the embedding API and GPT-based generative model.


# RAG-clinical-diagnosis

Uses FAISS to perform nearest-neighbor search on vector embeddings of medical documents.

Utilizes OpenAI's text-embedding-ada-002 for query embeddings.

Generates responses with OpenAI's GPT-4 Turbo model, strictly constrained to context from relevant documents.

Ensures safety and caution in responses by following strict medical prompt guidelines.

Ready-to-use for building medical chatbots that rely only on curated knowledge sources.

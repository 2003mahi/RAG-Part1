# RAG-Part1
Build a Retrieval Augmented Generation (RAG) App: Part 1


A typical RAG application has two main components:

**Indexing:** a pipeline for ingesting data from a source and indexing it. This usually happens offline.

**Retrieval and generation:** the actual RAG chain, which takes the user query at run time and retrieves the relevant data from the index, then passes that to the model.

This **Repo** will show how to build a simple Q&A application over a text data source. Along the way we’ll go over a typical Q&A architecture and highlight additional resources for more advanced Q&A techniques. We’ll also see how LangSmith can help us trace and understand our application. LangSmith will become increasingly helpful as our application grows in complexity...

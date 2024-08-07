# Improving Real-World RAG Systems - Key Challenges and Practical Solutions

![](https://i.imgur.com/ZdpFHzB.png)

Everyone knows how to build RAG systems, but how do you improve them? Retrieval Augmented Generation (RAG) systems have quickly become among the industry's biggest successes for driving Generative AI use cases on custom enterprise data. However, with their success comes a whole list of pain points that can lead to failure or sub-optimal performance in RAG systems. 

This session is inspired by the famous paper “Seven Failure Points When Engineering a Retrieval Augmented Generation System” by Barnett et al., which discusses some of the major challenges and points of failure in RAG Systems. However, clear solutions to these challenges are not mentioned in detail.

![](https://i.imgur.com/HOvpTdQ.png)

This session aims to bridge this gap where we will cover the major challenges and pain points when building real-world RAG systems, which include:

1. Missing Content
2. Missed the Top Ranked Documents
3. Not in Context 
4. Not Extracted
5. Wrong Format
6. Incorrect Specificity
7. Incomplete
   
Besides discussing the challenges, we will also discuss practical solutions of how we could address these challenges using the latest and best techniques, including:

- Better data cleaning and prompting 
- More intelligent chunking 
- Better retrieval strategies like Reranking and Compression
- Effect of embedding models and how can we fine-tune such models
- Output parsers for better response format adherence
- Query transformations
- Latest advancements in RAG systems like GraphRAG, Agentic RAG, CRAG, RAFT, etc
- Can long-context LLMs help?

The overall structure of the talk would involve discussing each challenge, discussing potential solutions, and also showcasing some of these with hands-on code leveraging popular frameworks like LangChain and LlamaIndex.

### Key Takeaways:

- Learn about the common challenges and pain points when building real-world RAG Systems
- Understand practical solutions for tackling each pain point which can lead to failure in RAG Systems
- Learn concepts and hands-on implementations of solutions, including data processing, chunking, reranking, embedding models, parsers, query transformers, and more
- Discuss some of the latest advancements in Generative AI and RAG systems like Agentic RAG, CRAG, RAFT, and long context LLMs

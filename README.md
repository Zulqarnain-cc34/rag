
1. **Adaptive RAG** ✔

Query Classification:

Factual, Analytical, Opinion and Contextual


**Factual Strategy**

    Enhances the original query using an LLM for better precision.
    Retrieves documents based on the enhanced query.
    Uses an LLM to rank documents by relevance.

**Analytical Strategy**

    Generates multiple sub-queries using an LLM to cover different aspects of the main query.
    Retrieves documents for each sub-query.
    Ensures diversity in the final document selection using an LLM.

**Opinion Strategy**

    Identifies different viewpoints on the topic using an LLM.
    Retrieves documents representing each viewpoint.
    Uses an LLM to select a diverse range of opinions from the retrieved documents.

**Contextual Strategy**

    Incorporates user-specific context into the query using an LLM.
    Performs retrieval based on the contextualized query.
    Ranks documents considering both relevance and user context.
    
![Company Logo](/images/adaptive_retrieval.svg)

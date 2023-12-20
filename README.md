Testing out langchain to see how good of a RAG pipeline I can implement in winter break 2023-2024

Best/most recent is in LC_2.

TODO:
1. Get 50 news examples
2. Finish fine tune code for M7b


Notes:

Need to think about ways to improve article querying.  For example, "updates on Ukraine" and "Ukraine updates" return different things entirely.  In fact, "Ukraine updates" came back with nothing, but is a reasonable thing to ask.  Might have to query for similar topics if the similarity is under a certain threshold.\n
Potential fixes:
- Similarity threshold with vectorspace of topics (I can explain)
- KG

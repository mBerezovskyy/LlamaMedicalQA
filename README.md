# LlamaMedicalQA

Own implementation of Refine chain for generative QA from langchain library.

> Technologies used: 
1. Llama2-13b
2. ctranslate2
3. chromadb
4. HuggingFace
5. langchain (some non-LLM components)

> Ran on Nvidia RTX A6000 GPU

The inference speed is faster than the vanilla HuggingFace pipeline.

Custom prompts lead to better quality, then base langchain implementation

> TODO:
1. Scrape more data from the American Cancer Society website
2. Try a bigger model e.g. llama2-70b
3. Implement automatical detection of the GPUs count to parallelize the computation
4. Perform further prompt engineering to fight hallucinations
5. Try another embedding NN
6. Experiment with context-aware chunking

> [!abstract]- Notion AI: RAG Reasoning and Prompt Case Study
> - This case study designs an LLM ranking methodology for Notion-augmented RAG chatbot responses.  Using A/B testing on 5 transcripts (each with two model responses), an LLM first generates a structured summary of the RAG retrieval trace guided by a five-dimension rubric (Clear, Relevant, Accurate, Functional, Transparent/Tone). We then programmatically validate summary faithfulness against the original transcript using a deterministic regex parser. A corrective loop re-queries the LLM with error evidence until all faithfulness checks pass. Perception quality of the LLM responses is measured separately via a Likert scale against the rubric.
> - A second study distills prompt-level interventions to ==reduced hallucination rate and promot relevance== runs without changing the model
> ### [Presentation](https://uxmichelleg.notion.site) 
> > [!info] #llm #uxui #RAG #explainability
>

^9447ac

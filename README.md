# Ehsan Barkhordar

Backend engineer in İstanbul. Python, mostly. M.Sc. Computer Science at Koç
University, where I worked on multilingual NLP: bias and hate speech detection
for under-resourced languages.

These days I spend most of my time in the guts of LLM agent tooling: message
conversion layers, retrieval scoring, token accounting, the places where small
correctness bugs quietly ruin results. When I hit one, I fix it upstream.

Recent open source work:

- [changedetection.io](https://github.com/dgtlmoon/changedetection.io/pull/4249): made the `restock` notification token safe outside restock watches (merged)
- [local-deep-research](https://github.com/LearningCircuit/local-deep-research/pull/5062): FAISS cosine scores were inverting the search ranking (in review)
- [swarms](https://github.com/kyegomez/swarms/pull/1712): stop sending empty text blocks to Anthropic on image-only vision calls (in review)
- more in flight in llama_index and camel

Every change I submit is reproduced first and ships with a test that fails
without the fix. I use AI tooling in my workflow and disclose it where
maintainers ask.

Elsewhere: [ebarkhordar.com](https://ebarkhordar.com)

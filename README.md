# Hi, I'm Rajesh

M.Tech in Computer Science and Engineering from the Indian Institute of Science (IISc). I work on machine learning, mainly recommender systems, and I am looking for data science and applied scientist roles in e-commerce.

## Featured project

**[fashion-recsys-hm](https://github.com/rajesh22764/fashion-recsys-hm)** is a two-stage fashion recommender (candidate retrieval, then a LightGBM ranker) on the H&M purchase data, built around an honest evaluation:

- Strict time-based evaluation, with a leak I found in my own setup fixed and covered by a test
- Ranker recall@12 about 71% higher (relative) than the best single candidate generator, and ahead of it in each of four consecutive test weeks
- Results averaged over repeated training seeds, with bootstrap confidence intervals
- A negative result reported as such: a two-tower neural retriever gave no reliable gain to the final ranker, though it helps on brand-new articles
- **[Live demo](https://fashion-recsys-hm.streamlit.app/)** with real recommendations and product images (precomputed, not live inference)

## Other projects

- **[atlas-copilot](https://github.com/rajesh22764/atlas-copilot)**: agentic RAG and text-to-SQL assistant with hybrid retrieval, LangGraph orchestration, an MCP tool server and a groundedness critic; runs on local open-weight models via Ollama
- **[har-activity-recognition](https://github.com/rajesh22764/har-activity-recognition)**: human activity recognition from smartphone sensors, with EDA, hypothesis tests, ML and deep learning comparison, SHAP and a Streamlit app

## Tools

Python, PyTorch, LightGBM, scikit-learn, pandas, NumPy, Streamlit, MATLAB

## Interests

The mathematics behind machine learning and deep learning, recommender systems, LLMs, computer vision and reinforcement learning.

# Hi, I'm Rajesh

I'm a machine learning engineer-in-the-making with an M.Tech in Computer Science and Engineering from the Indian Institute of Science (IISc), working mainly on recommender systems. I'm looking for data science and applied scientist roles in e-commerce and other ML-driven product teams.

## About me

- **Now:** Research Assistant at IISc, building machine learning tutorial material in MATLAB for an edge-AI course.
- **Before:** Worked at Mobius in 2025, after completing my M.Tech (CSE, IISc, 2023 to 2025). Earlier, B.Tech in CSE at JNTUA College of Engineering, Pulivendula. GATE (Computer Science) 2023 rank: 1210.
- **What I like:** the mathematics behind machine learning, and checking my own results properly. I report confidence intervals, repeat experiments across seeds, and publish negative results as negative results.
- **How I work:** I'd rather ship one project I can defend line by line than five I can only demo. My main project went through several review rounds; each time I found something wrong in my own setup, fixed it, and wrote it down in the README.
- **Looking for:** a team where I can work on ranking, retrieval or personalisation, learn from stronger engineers, and be measured by evidence.

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

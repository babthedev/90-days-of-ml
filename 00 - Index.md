# 90 Days of ML: Master Tracker & Checklist 🚀

Welcome to your **90 Days of Machine Learning** master roadmap. Every single day is mapped out below with actionable objectives, resources, and completion criteria. You can check off each item directly in Obsidian as you complete them!

> [!TIP]
> Changes and completed checkboxes automatically sync with your GitHub repository via **Obsidian Git**.
> Relevant links: [[LEARNING|LEARNING.md (Concept Logs & Cohort Dates)]] | [[Day 01 - Intro & Setup|Day 01 Note]]

---

## 🏆 Gates & Milestones
- [ ] **Gate 1 (Oct 31):** FlyRank Foundation Assignments 1–5 submitted
- [ ] **Gate 2 (Nov 30):** P1 Capstone submitted + tiny GPT trained from scratch
- [ ] **Gate 3 (Dec 31):** P2 RAG Live + P3 LoRA fine-tuned + 15 Job Applications sent

---

## 📅 Phase 1 — October: Classical ML + FlyRank Foundations (Days 1–31)
> **Goal:** Train, validate and explain classical models on real data; submit all 5 FlyRank foundation assignments by Oct 31.

- [ ] **[[Day 01 - Setup|Day 01 (Thu Oct 1)]]** — **Setup**: Check FlyRank dashboard (cohort end date, assignment list, capstone deadline). Set up Colab + Kaggle accounts, create repo, start `LEARNING.md`.  
  *Done when:* Cohort end date is written at the top of [[LEARNING]]
- [ ] **[[Day 02 - pandas|Day 02 (Fri Oct 2)]]** — **pandas**: [Kaggle Learn: Pandas](https://www.kaggle.com/learn/pandas), all 6 lessons.  
  *Done when:* Every exercise passes
- [ ] **[[Day 03 - FlyRank|Day 03 (Sat Oct 3)]]** — **FlyRank**: Onboarding + Assignment 1 (starter notebooks, research question).  
  *Done when:* A1 submitted
- [ ] **[[Day 04 - Review|Day 04 (Sun Oct 4)]]** — **Review**: Weekly review template.  
  *Done when:* Post #1 is up (why you're starting)
- [ ] **[[Day 05 - Linear regression|Day 05 (Mon Oct 5)]]** — **Linear regression**: MLCC "Linear regression" + StatQuest "Linear Regression, Clearly Explained". Fit sklearn LinearRegression on California Housing.  
  *Done when:* Notebook reports RMSE
- [ ] **[[Day 06 - Gradient descent|Day 06 (Tue Oct 6)]]** — **Gradient descent**: StatQuest "Gradient Descent, Step-by-Step". Write linear regression with gradient descent in NumPy.  
  *Done when:* Your weights match sklearn's within 1%
- [ ] **[[Day 07 - Logistic regression|Day 07 (Wed Oct 7)]]** — **Logistic regression**: MLCC "Logistic regression" + "Classification". sklearn LogisticRegression on [Titanic](https://www.kaggle.com/competitions/titanic).  
  *Done when:* Titanic submission #1
- [ ] **[[Day 08 - Overfitting|Day 08 (Thu Oct 8)]]** — **Overfitting**: MLCC "Datasets, generalization, and overfitting". Plot train vs validation error across polynomial degrees, then add Ridge and Lasso.  
  *Done when:* Learning-curve plot is committed
- [ ] **[[Day 09 - Consolidate|Day 09 (Fri Oct 9)]]** — **Consolidate**: [Kaggle Learn: Intro to ML](https://www.kaggle.com/learn/intro-to-machine-learning), all 7 lessons.  
  *Done when:* Course certificate
- [ ] **[[Day 10 - FlyRank|Day 10 (Sat Oct 10)]]** — **FlyRank**: Assignment 2: frame your lane as an ML task (target label, metric, loss).  
  *Done when:* A2 submitted
- [ ] **[[Day 11 - Review|Day 11 (Sun Oct 11)]]** — **Review**: Rebuild Day 6 (gradient descent) from blank.  
  *Done when:* Post #2
- [ ] **[[Day 12 - Metrics|Day 12 (Mon Oct 12)]]** — **Metrics**: StatQuest "ROC and AUC" + the sklearn metrics guide. Compute precision, recall, F1, ROC-AUC and precision@k for your Titanic model, by hand and then with sklearn.  
  *Done when:* Hand and sklearn numbers match
- [ ] **[[Day 13 - Pipelines + CV|Day 13 (Tue Oct 13)]]** — **Pipelines + CV**: [Kaggle Learn: Intermediate ML](https://www.kaggle.com/learn/intermediate-machine-learning), lessons 1–5.  
  *Done when:* Pipeline scored with 5-fold CV
- [ ] **[[Day 14 - Trees + forests|Day 14 (Wed Oct 14)]]** — **Trees + forests**: StatQuest "Decision Trees" + "Random Forests". Random forest on Titanic with feature importances.  
  *Done when:* Submission #2 beats #1
- [ ] **[[Day 15 - Boosting|Day 15 (Thu Oct 15)]]** — **Boosting**: StatQuest "Gradient Boost Part 1" + "XGBoost Part 1". Intermediate ML lessons 6–7 (XGBoost, data leakage).  
  *Done when:* XGBoost model uses early stopping
- [ ] **[[Day 16 - Tuning + grouped splits|Day 16 (Fri Oct 16)]]** — **Tuning + grouped splits**: sklearn RandomizedSearchCV, GroupKFold, GroupShuffleSplit. Show how much an ungrouped split inflates the score.  
  *Done when:* You've written down the inflated vs honest score
- [ ] **[[Day 17 - FlyRank|Day 17 (Sat Oct 17)]]** — **FlyRank**: Assignment 3: data contract, features, validation strategy.  
  *Done when:* A3 submitted
- [ ] **[[Day 18 - Review|Day 18 (Sun Oct 18)]]** — **Review**: Rebuild the Day 16 grouped split.  
  *Done when:* Post #3: what data leakage is
- [ ] **[[Day 19 - Feature engineering|Day 19 (Mon Oct 19)]]** — **Feature engineering**: [Kaggle Learn: Feature Engineering](https://www.kaggle.com/learn/feature-engineering), lessons 1–4 (mutual information, creating features, k-means features).  
  *Done when:* Exercises pass
- [ ] **[[Day 20 - PCA + encoding|Day 20 (Tue Oct 20)]]** — **PCA + encoding**: Feature Engineering lessons 5–6 + StatQuest "PCA, Step-by-Step".  
  *Done when:* Exercises pass
- [ ] **[[Day 21 - Clustering|Day 21 (Wed Oct 21)]]** — **Clustering**: StatQuest "K-means clustering" + HDBSCAN docs "How HDBSCAN Works". Run k-means, DBSCAN and HDBSCAN on one dataset.  
  *Done when:* 3 methods compared in one notebook
- [ ] **[[Day 22 - Embeddings|Day 22 (Thu Oct 22)]]** — **Embeddings**: [The Illustrated Word2vec](https://jalammar.github.io/illustrated-word2vec/) + the sbert.net quickstart. Embed ~1,000 titles or queries with all-MiniLM-L6-v2 and add cosine-similarity search.  
  *Done when:* Semantic search returns sensible neighbours
- [ ] **[[Day 23 - Topic clustering|Day 23 (Fri Oct 23)]]** — **Topic clustering**: UMAP + HDBSCAN on those embeddings. Use the BERTopic docs as a reference. Label every cluster.  
  *Done when:* Named clusters on a real keyword or query set
- [ ] **[[Day 24 - FlyRank|Day 24 (Sat Oct 24)]]** — **FlyRank**: Assignment 4: baseline score + review.  
  *Done when:* A4 submitted
- [ ] **[[Day 25 - Review|Day 25 (Sun Oct 25)]]** — **Review**: Rebuild Day 22 semantic search from blank.  
  *Done when:* Post #4
- [ ] **[[Day 26 - Linear algebra|Day 26 (Mon Oct 26)]]** — **Linear algebra**: 3Blue1Brown Essence of Linear Algebra, ch 1–4. Do the same operations in NumPy.  
  *Done when:* Matrix-multiply notebook
- [ ] **[[Day 27 - Dot products|Day 27 (Tue Oct 27)]]** — **Dot products**: Essence of Linear Algebra, ch 9 (dot products). Implement cosine similarity yourself.  
  *Done when:* Your version matches sklearn's
- [ ] **[[Day 28 - Calculus|Day 28 (Wed Oct 28)]]** — **Calculus**: 3Blue1Brown Essence of Calculus, ch 1–4 (derivatives, chain rule).  
  *Done when:* You've derived the MSE gradient by hand
- [ ] **[[Day 29 - Probability|Day 29 (Thu Oct 29)]]** — **Probability**: StatQuest "Probability is not Likelihood", "Maximum Likelihood" and "Cross Entropy".  
  *Done when:* Log loss explained in 5 sentences in [[LEARNING]]
- [ ] **[[Day 30 - ML judgement|Day 30 (Fri Oct 30)]]** — **ML judgement**: [Rules of ML](https://developers.google.com/machine-learning/guides/rules-of-ml), full read.  
  *Done when:* A 10-point checklist for your capstone
- [ ] **[[Day 31 - FlyRank (Gate 1)|Day 31 (Sat Oct 31)]]** — **FlyRank**: Assignment 5.  
  *Done when:* **Gate 1:** A1–A5 submitted

---

## 📅 Phase 2 — November: Capstone, Deep Learning, Transformers (Days 32–61)
> **Goal:** Submit the FlyRank capstone by Nov 9, then go from backprop to training a small GPT yourself by Nov 30.

- [ ] **[[Day 32 - Review + plan|Day 32 (Sun Nov 1)]]** — **Review + plan**: Check Gate 1. Write a one-page capstone plan: question, data, target, metric, baseline.  
  *Done when:* Plan is committed
- [ ] **[[Day 33 - Capstone (EDA)|Day 33 (Mon Nov 2)]]** — **Capstone**: Load the data, do EDA, lock the target and metric (e.g. precision@50).  
  *Done when:* EDA notebook
- [ ] **[[Day 34 - Capstone (Baseline)|Day 34 (Tue Nov 3)]]** — **Capstone**: A naive rule-based baseline and a reusable evaluation function.  
  *Done when:* You have a baseline number
- [ ] **[[Day 35 - Capstone (Grouped Splits)|Day 35 (Wed Nov 4)]]** — **Capstone**: Features + a grouped validation split (split by client or domain).  
  *Done when:* No group appears in both train and test
- [ ] **[[Day 36 - Capstone (Models)|Day 36 (Thu Nov 5)]]** — **Capstone**: Random forest / XGBoost + tuning.  
  *Done when:* Beats the baseline on the grouped split
- [ ] **[[Day 37 - Capstone (Audit)|Day 37 (Fri Nov 6)]]** — **Capstone**: Leakage audit + error analysis: where does the model fail, and why?  
  *Done when:* Written list of the top 3 failure patterns
- [ ] **[[Day 38 - Capstone (Reproducibility)|Day 38 (Sat Nov 7)]]** — **Capstone**: Recommendations layer + reproducibility (pinned requirements, fixed seed, one-command run).  
  *Done when:* Runs cleanly in a fresh Colab
- [ ] **[[Day 39 - Review|Day 39 (Sun Nov 8)]]** — **Review**: Re-run the whole capstone from a clean clone.  
  *Done when:* No errors
- [ ] **[[Day 40 - Capstone ship (P1)|Day 40 (Mon Nov 9)]]** — **Capstone ship**: README (problem, approach, baseline vs model, limits) + presentation outline. Submit the public link.  
  *Done when:* P1 submitted
- [ ] **[[Day 41 - Neural nets|Day 41 (Tue Nov 10)]]** — **Neural nets**: 3Blue1Brown Neural Networks, ch 1–2.  
  *Done when:* Notes on neurons, weights, loss
- [ ] **[[Day 42 - Backprop|Day 42 (Wed Nov 11)]]** — **Backprop**: 3Blue1Brown Neural Networks, ch 3–4.  
  *Done when:* Backprop explained in your own words
- [ ] **[[Day 43 - micrograd (Part 1)|Day 43 (Thu Nov 12)]]** — **micrograd (1/2)**: Karpathy "Building micrograd", first half, coding along.  
  *Done when:* Value class with backward() works
- [ ] **[[Day 44 - micrograd (Part 2)|Day 44 (Fri Nov 13)]]** — **micrograd (2/2)**: Second half: neuron, layer, MLP, training loop.  
  *Done when:* Your MLP's loss goes down
- [ ] **[[Day 45 - Buffer|Day 45 (Sat Nov 14)]]** — **Buffer**: Capstone revisions if the reviewer asked for changes. If not, PyTorch "Tensors" + "Datasets & DataLoaders".  
  *Done when:* Revisions resubmitted, or tutorial done
- [ ] **[[Day 46 - Review|Day 46 (Sun Nov 15)]]** — **Review**: Rebuild micrograd's backward() from blank.  
  *Done when:* Post #5: capstone results
- [ ] **[[Day 47 - PyTorch (Part 1)|Day 47 (Mon Nov 16)]]** — **PyTorch (1/2)**: [Learn the Basics](https://pytorch.org/tutorials/beginner/basics/intro.html): tensors, data, build model.  
  *Done when:* Tutorial notebook
- [ ] **[[Day 48 - PyTorch (Part 2)|Day 48 (Tue Nov 17)]]** — **PyTorch (2/2)**: Autograd, optimization loop, save/load.  
  *Done when:* FashionMNIST above 85% accuracy
- [ ] **[[Day 49 - makemore 1 (Part 1)|Day 49 (Wed Nov 18)]]** — **makemore 1 (1/2)**: Karpathy makemore part 1 (bigram), first half.  
  *Done when:* Counting bigram model
- [ ] **[[Day 50 - makemore 1 (Part 2)|Day 50 (Thu Nov 19)]]** — **makemore 1 (2/2)**: Second half: the neural-net version of the bigram.  
  *Done when:* Loss matches the counting model
- [ ] **[[Day 51 - makemore 2 (Part 1)|Day 51 (Fri Nov 20)]]** — **makemore 2 (1/2)**: makemore part 2 (MLP), first half.  
  *Done when:* Embedding + hidden layer built
- [ ] **[[Day 52 - makemore 2 (Part 2)|Day 52 (Sat Nov 21)]]** — **makemore 2 (2/2)**: Second half: train/dev/test split, tuning.  
  *Done when:* Generates plausible names
- [ ] **[[Day 53 - Review|Day 53 (Sun Nov 22)]]** — **Review**: Rebuild the PyTorch training loop from blank.  
  *Done when:* Post #6
- [ ] **[[Day 54 - Transfer learning|Day 54 (Mon Nov 23)]]** — **Transfer learning**: [fast.ai](https://course.fast.ai/) Lesson 1 on a Kaggle GPU.  
  *Done when:* Your own image classifier
- [ ] **[[Day 55 - CNNs|Day 55 (Tue Nov 24)]]** — **CNNs**: StatQuest "Neural Networks Part 8: Image Classification with CNNs". A CNN in PyTorch on CIFAR-10.  
  *Done when:* Beats the MLP baseline
- [ ] **[[Day 56 - Deploy a model|Day 56 (Wed Nov 25)]]** — **Deploy a model**: fast.ai Lesson 2: Gradio + Hugging Face Spaces.  
  *Done when:* Your first live model URL
- [ ] **[[Day 57 - Attention|Day 57 (Thu Nov 26)]]** — **Attention**: 3Blue1Brown Neural Networks, ch 5–6 (transformers, attention).  
  *Done when:* Attention sketched on paper
- [ ] **[[Day 58 - Transformer architecture|Day 58 (Fri Nov 27)]]** — **Transformer architecture**: [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/).  
  *Done when:* Architecture diagram redrawn from memory
- [ ] **[[Day 59 - GPT (Part 1)|Day 59 (Sat Nov 28)]]** — **GPT (1/2)**: Karpathy "Let's build GPT", up to self-attention.  
  *Done when:* Self-attention head in code
- [ ] **[[Day 60 - Review|Day 60 (Sun Nov 29)]]** — **Review**: Rebuild self-attention from blank.  
  *Done when:* Post #7
- [ ] **[[Day 61 - GPT (Part 2) (Gate 2)|Day 61 (Mon Nov 30)]]** — **GPT (2/2)**: Finish "Let's build GPT": multi-head attention, blocks, training.  
  *Done when:* **Gate 2:** capstone in, tiny GPT trained

---

## 📅 Phase 3 — December: LLM Engineering, Deployment, Job Launch (Days 62–92)
> **Goal:** Ship a RAG app with measured quality and a fine-tuned model behind an API, then spend the last week getting in front of employers.

- [ ] **[[Day 62 - Hugging Face|Day 62 (Tue Dec 1)]]** — **Hugging Face**: [LLM Course](https://huggingface.co/learn/llm-course), ch 1–2 (pipelines, tokenizers, models).  
  *Done when:* Tokenize and run 3 models
- [ ] **[[Day 63 - Fine-tune an encoder|Day 63 (Wed Dec 2)]]** — **Fine-tune an encoder**: LLM Course ch 3: fine-tune a BERT-style model for text classification (e.g. search-query intent).  
  *Done when:* You have an eval F1
- [ ] **[[Day 64 - LLM APIs + prompting|Day 64 (Thu Dec 3)]]** — **LLM APIs + prompting**: [Anthropic prompt engineering guide](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview). Use a free-tier API to extract structured JSON from 50 texts.  
  *Done when:* At least 45/50 parse cleanly
- [ ] **[[Day 65 - Vector search|Day 65 (Fri Dec 4)]]** — **Vector search**: [Patterns for LLM systems](https://eugeneyan.com/writing/llm-patterns/) (RAG section). Chunk a corpus and index it in Chroma or pgvector.  
  *Done when:* Top-5 retrieval works
- [ ] **Day 66 (Sat Dec 5)** — **P2: RAG v1**: Answer questions over a real corpus, with citations. Suggested corpus: creator-community FAQs or docs.  
  *Done when:* Works locally
- [ ] **[[Day 67 - Review|Day 67 (Sun Dec 6)]]** — **Review**: Rebuild the Day 65 chunk → embed → retrieve pipeline from blank.  
  *Done when:* Post #8
- [ ] **[[Day 68 - Evals|Day 68 (Mon Dec 7)]]** — **Evals**: [Your AI Product Needs Evals](https://hamel.dev/blog/posts/evals/). Write 30 test questions. Measure retrieval hit rate and answer correctness (LLM-as-judge, spot-checked by you).  
  *Done when:* Baseline eval scores
- [ ] **[[Day 69 - Improve RAG|Day 69 (Tue Dec 8)]]** — **Improve RAG**: Hybrid search (BM25 + vectors) + a cross-encoder reranker from sbert.net.  
  *Done when:* Eval scores beat the v1 baseline
- [ ] **[[Day 70 - Tool use|Day 70 (Wed Dec 9)]]** — **Tool use**: [Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents). Add one tool-calling step to P2.  
  *Done when:* Tool call runs end to end
- [ ] **[[Day 71 - P2 ship|Day 71 (Thu Dec 10)]]** — **P2 ship**: Gradio UI → Hugging Face Spaces. README with before/after eval numbers.  
  *Done when:* P2 live
- [ ] **[[Day 72 - Fine-tuning theory|Day 72 (Fri Dec 11)]]** — **Fine-tuning theory**: PEFT docs, LoRA conceptual guide. When to prompt vs RAG vs fine-tune.  
  *Done when:* One-page decision note
- [ ] **Day 73 (Sat Dec 12)** — **P3: LoRA (1/2)**: [Unsloth](https://docs.unsloth.ai/) Colab notebook: LoRA-fine-tune a ~1B model on a narrow task.  
  *Done when:* Training finishes
- [ ] **[[Day 74 - Review|Day 74 (Sun Dec 13)]]** — **Review**: Rebuild the P2 eval harness from blank.  
  *Done when:* Post #9: P2 eval results
- [ ] **Day 75 (Mon Dec 14)** — **P3: LoRA (2/2)**: Compare the base, prompted and fine-tuned models on held-out data. Push the adapter to the Hugging Face Hub.  
  *Done when:* Comparison table in README
- [ ] **[[Day 76 - Serving|Day 76 (Tue Dec 15)]]** — **Serving**: [FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/). Put a /predict endpoint in front of P3 (or the P1 model if P3 is too heavy for CPU).  
  *Done when:* Endpoint returns predictions
- [ ] **[[Day 77 - Docker|Day 77 (Wed Dec 16)]]** — **Docker**: [Docker Get Started](https://docs.docker.com/get-started/). Containerize the API.  
  *Done when:* P3: docker run serves predictions
- [ ] **[[Day 78 - Experiment tracking|Day 78 (Thu Dec 17)]]** — **Experiment tracking**: [MLflow](https://mlflow.org/docs/latest/) quickstart. Log your P1 runs.  
  *Done when:* Runs are comparable in the MLflow UI
- [ ] **[[Day 79 - Testing + CI|Day 79 (Fri Dec 18)]]** — **Testing + CI**: [Made With ML](https://madewithml.com/): testing lessons. GitHub Actions runs your tests on every push.  
  *Done when:* Green CI badge
- [ ] **[[Day 80 - Monitoring|Day 80 (Sat Dec 19)]]** — **Monitoring**: [Evidently](https://docs.evidentlyai.com/) quickstart. Build a drift report on the P1 data.  
  *Done when:* Drift report is committed
- [ ] **[[Day 81 - Review|Day 81 (Sun Dec 20)]]** — **Review**: Redeploy P2 from a clean clone.  
  *Done when:* Post #10
- [ ] **[[Day 82 - System design (Part 1)|Day 82 (Mon Dec 21)]]** — **System design (1/2)**: [CS329S](https://stanford-cs329s.github.io/) notes. Design a content-decay alerting system: data, model, serving, monitoring.  
  *Done when:* 1-page design doc
- [ ] **[[Day 83 - System design (Part 2)|Day 83 (Tue Dec 22)]]** — **System design (2/2)**: Design a RAG support bot for 10k creators, covering latency, cost and evals.  
  *Done when:* 1-page design doc
- [ ] **[[Day 84 - Portfolio|Day 84 (Wed Dec 23)]]** — **Portfolio**: Each project README gets problem, approach, metric, result, demo link and how to run. Pin P1–P3 on GitHub.  
  *Done when:* 3 polished repos
- [ ] **[[Day 85 - Interview theory|Day 85 (Thu Dec 24)]]** — **Interview theory**: [ML Interviews Book](https://huyenchip.com/ml-interviews-book/): answer 20 ML fundamentals questions out loud.  
  *Done when:* 20 answers written
- [ ] **[[Day 86 - Interview coding|Day 86 (Fri Dec 25)]]** — **Interview coding**: From scratch in NumPy: kNN, k-means, logistic regression. Plus 3 pandas/SQL problems.  
  *Done when:* All 6 pass your tests
- [ ] **[[Day 87 - Long-form post|Day 87 (Sat Dec 26)]]** — **Long-form post**: "90 days of ML": what you built, with links and results.  
  *Done when:* Published
- [ ] **[[Day 88 - Review|Day 88 (Sun Dec 27)]]** — **Review**: Record a 3-minute walkthrough of each project.  
  *Done when:* 3 recordings
- [ ] **[[Day 89 - CV + LinkedIn|Day 89 (Mon Dec 28)]]** — **CV + LinkedIn**: Rewrite the FlyRank experience with metrics (e.g. "2× lift over baseline"), add Featured projects and a new headline.  
  *Done when:* CV PDF + updated profile
- [ ] **[[Day 90 - Applications|Day 90 (Tue Dec 29)]]** — **Applications**: Shortlist 30 roles (remote AI/ML engineer on [Wellfound](https://wellfound.com/) and [Work at a Startup](https://www.workatastartup.com/), plus Nigerian tech companies). Send 5 applications.  
  *Done when:* 5 applications sent
- [ ] **[[Day 91 - Applications|Day 91 (Wed Dec 30)]]** — **Applications**: Send 5 more. Message 5 engineers at your target companies.  
  *Done when:* 10 applications sent
- [ ] **[[Day 92 - Retro (Gate 3)|Day 92 (Thu Dec 31)]]** — **Retro**: Send 5 more. Write a Q1 2027 plan based on where you're weakest.  
  *Done when:* **Gate 3:** 15 sent, P2 live

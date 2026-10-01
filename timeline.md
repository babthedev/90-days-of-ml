# 90 Days of ML: Interactive Master Timeline & Checklist 🗓️

> [!TIP]
> This timeline is fully interactive in Obsidian! Click any checkbox `- [ ]` to mark a day or milestone complete. Your progress automatically syncs with GitHub via **Obsidian Git**.

---

## 🏆 Key Gates & Capstone Milestones

- [ ] **Gate 1 (Oct 31):** FlyRank Foundation Assignments 1–5 submitted
- [ ] **Capstone P1 (Nov 9):** Capstone project shipped with public link
- [ ] **Gate 2 (Nov 30):** Capstone submitted + tiny GPT trained from scratch
- [ ] **Gate 3 (Dec 31):** P2 RAG Live + P3 LoRA Fine-Tuned + 15 Job Applications sent

---

## 📅 Phase 1 — October: Classical ML + FlyRank Foundations (Days 1–31)

**Monthly Goal:** Train, validate, and explain classical models on real data, and get all 5 FlyRank foundation assignments submitted by Oct 31.

- [ ] **[[Day 01 - Setup|Day 01 (Thu Oct 1)]]**: **Setup**
  - **Do:** Check your FlyRank dashboard for the cohort end date, assignment list, and capstone deadline. Set up Colab + Kaggle accounts, create the repository, and start [[LEARNING|LEARNING.md]].
  - **Done when:** Cohort end date is written at the top of [[LEARNING|LEARNING.md]]

- [ ] **[[Day 02 - pandas|Day 02 (Fri Oct 2)]]**: **pandas**
  - **Do:** [Kaggle Learn: Pandas](https://www.kaggle.com/learn/pandas), all 6 lessons.
  - **Done when:** Every exercise passes

- [ ] **[[Day 03 - FlyRank|Day 03 (Sat Oct 3)]]**: **FlyRank**
  - **Do:** Onboarding + Assignment 1 (starter notebooks, research question).
  - **Done when:** A1 submitted

- [ ] **[[Day 04 - Review|Day 04 (Sun Oct 4)]]**: **Review**
  - **Do:** Weekly review template.
  - **Done when:** Post #1 is up (why you're starting)

- [ ] **[[Day 05 - Linear regression|Day 05 (Mon Oct 5)]]**: **Linear regression**
  - **Do:** MLCC "Linear regression" + StatQuest "Linear Regression, Clearly Explained". Fit sklearn `LinearRegression` on California Housing.
  - **Done when:** Notebook reports RMSE

- [ ] **[[Day 06 - Gradient descent|Day 06 (Tue Oct 6)]]**: **Gradient descent**
  - **Do:** StatQuest "Gradient Descent, Step-by-Step". Write linear regression with gradient descent in NumPy.
  - **Done when:** Your weights match sklearn's within 1%

- [ ] **[[Day 07 - Logistic regression|Day 07 (Wed Oct 7)]]**: **Logistic regression**
  - **Do:** MLCC "Logistic regression" + "Classification". sklearn `LogisticRegression` on [Titanic](https://www.kaggle.com/competitions/titanic).
  - **Done when:** Titanic submission #1

- [ ] **[[Day 08 - Overfitting|Day 08 (Thu Oct 8)]]**: **Overfitting**
  - **Do:** MLCC "Datasets, generalization, and overfitting". Plot train vs validation error across polynomial degrees, then add Ridge and Lasso.
  - **Done when:** Learning-curve plot is committed

- [ ] **[[Day 09 - Consolidate|Day 09 (Fri Oct 9)]]**: **Consolidate**
  - **Do:** [Kaggle Learn: Intro to ML](https://www.kaggle.com/learn/intro-to-machine-learning), all 7 lessons.
  - **Done when:** Course certificate obtained

- [ ] **[[Day 10 - FlyRank|Day 10 (Sat Oct 10)]]**: **FlyRank**
  - **Do:** Assignment 2: Frame your lane as an ML task (target label, metric, loss).
  - **Done when:** A2 submitted

- [ ] **[[Day 11 - Review|Day 11 (Sun Oct 11)]]**: **Review**
  - **Do:** Rebuild Day 6 (gradient descent) from blank.
  - **Done when:** Post #2 is published

- [ ] **[[Day 12 - Metrics|Day 12 (Mon Oct 12)]]**: **Metrics**
  - **Do:** StatQuest "ROC and AUC" + the sklearn metrics guide. Compute precision, recall, F1, ROC-AUC, and precision@k for your Titanic model, by hand and then with sklearn.
  - **Done when:** Hand and sklearn numbers match

- [ ] **[[Day 13 - Pipelines + CV|Day 13 (Tue Oct 13)]]**: **Pipelines + CV**
  - **Do:** [Kaggle Learn: Intermediate ML](https://www.kaggle.com/learn/intermediate-machine-learning), lessons 1–5.
  - **Done when:** Pipeline scored with 5-fold CV

- [ ] **[[Day 14 - Trees + forests|Day 14 (Wed Oct 14)]]**: **Trees + forests**
  - **Do:** StatQuest "Decision Trees" + "Random Forests". Random forest on Titanic with feature importances.
  - **Done when:** Submission #2 beats #1

- [ ] **[[Day 15 - Boosting|Day 15 (Thu Oct 15)]]**: **Boosting**
  - **Do:** StatQuest "Gradient Boost Part 1" + "XGBoost Part 1". Intermediate ML lessons 6–7 (XGBoost, data leakage).
  - **Done when:** XGBoost model uses early stopping

- [ ] **[[Day 16 - Tuning + grouped splits|Day 16 (Fri Oct 16)]]**: **Tuning + grouped splits**
  - **Do:** sklearn `RandomizedSearchCV`, `GroupKFold`, `GroupShuffleSplit`. Show how much an ungrouped split inflates the score.
  - **Done when:** You've written down the inflated vs honest score

- [ ] **[[Day 17 - FlyRank|Day 17 (Sat Oct 17)]]**: **FlyRank**
  - **Do:** Assignment 3: Data contract, features, validation strategy.
  - **Done when:** A3 submitted

- [ ] **[[Day 18 - Review|Day 18 (Sun Oct 18)]]**: **Review**
  - **Do:** Rebuild the Day 16 grouped split from scratch.
  - **Done when:** Post #3: What data leakage is

- [ ] **[[Day 19 - Feature engineering|Day 19 (Mon Oct 19)]]**: **Feature engineering**
  - **Do:** [Kaggle Learn: Feature Engineering](https://www.kaggle.com/learn/feature-engineering), lessons 1–4 (mutual information, creating features, k-means features).
  - **Done when:** Exercises pass

- [ ] **[[Day 20 - PCA + encoding|Day 20 (Tue Oct 20)]]**: **PCA + encoding**
  - **Do:** Feature Engineering lessons 5–6 + StatQuest "PCA, Step-by-Step".
  - **Done when:** Exercises pass

- [ ] **[[Day 21 - Clustering|Day 21 (Wed Oct 21)]]**: **Clustering**
  - **Do:** StatQuest "K-means clustering" + HDBSCAN docs "How HDBSCAN Works". Run k-means, DBSCAN, and HDBSCAN on one dataset.
  - **Done when:** 3 methods compared in one notebook

- [ ] **[[Day 22 - Embeddings|Day 22 (Thu Oct 22)]]**: **Embeddings**
  - **Do:** [The Illustrated Word2vec](https://jalammar.github.io/illustrated-word2vec/) + the sbert.net quickstart. Embed ~1,000 titles or queries with `all-MiniLM-L6-v2` and add cosine-similarity search.
  - **Done when:** Semantic search returns sensible neighbours

- [ ] **[[Day 23 - Topic clustering|Day 23 (Fri Oct 23)]]**: **Topic clustering**
  - **Do:** UMAP + HDBSCAN on those embeddings. Use the BERTopic docs as a reference. Label every cluster.
  - **Done when:** Named clusters on a real keyword or query set

- [ ] **[[Day 24 - FlyRank|Day 24 (Sat Oct 24)]]**: **FlyRank**
  - **Do:** Assignment 4: Baseline score + review.
  - **Done when:** A4 submitted

- [ ] **[[Day 25 - Review|Day 25 (Sun Oct 25)]]**: **Review**
  - **Do:** Rebuild Day 22 semantic search from blank.
  - **Done when:** Post #4 is published

- [ ] **[[Day 26 - Linear algebra|Day 26 (Mon Oct 26)]]**: **Linear algebra**
  - **Do:** 3Blue1Brown Essence of Linear Algebra, ch 1–4. Do the same operations in NumPy.
  - **Done when:** Matrix-multiply notebook created and committed

- [ ] **[[Day 27 - Dot products|Day 27 (Tue Oct 27)]]**: **Dot products**
  - **Do:** Essence of Linear Algebra, ch 9 (dot products). Implement cosine similarity yourself.
  - **Done when:** Your version matches sklearn's

- [ ] **[[Day 28 - Calculus|Day 28 (Wed Oct 28)]]**: **Calculus**
  - **Do:** 3Blue1Brown Essence of Calculus, ch 1–4 (derivatives, chain rule).
  - **Done when:** You've derived the MSE gradient by hand

- [ ] **[[Day 29 - Probability|Day 29 (Thu Oct 29)]]**: **Probability**
  - **Do:** StatQuest "Probability is not Likelihood", "Maximum Likelihood", and "Cross Entropy".
  - **Done when:** Log loss explained in 5 sentences in [[LEARNING|LEARNING.md]]

- [ ] **[[Day 30 - ML judgement|Day 30 (Fri Oct 30)]]**: **ML judgement**
  - **Do:** [Rules of ML](https://developers.google.com/machine-learning/guides/rules-of-ml), full read.
  - **Done when:** A 10-point checklist for your capstone written in [[LEARNING|LEARNING.md]]

- [ ] **[[Day 31 - FlyRank (Gate 1)|Day 31 (Sat Oct 31)]]**: **FlyRank (Gate 1)**
  - **Do:** Assignment 5 finalization and submission.
  - **Done when:** **Gate 1:** A1–A5 all submitted

---

## 📅 Phase 2 — November: Capstone, Deep Learning, Transformers (Days 32–61)

**Monthly Goal:** Submit the FlyRank capstone by Nov 9, then go from backprop to training a small GPT yourself by Nov 30.

- [ ] **[[Day 32 - Review + plan|Day 32 (Sun Nov 1)]]**: **Review + plan**
  - **Do:** Check Gate 1. Write a one-page capstone plan: question, data, target, metric, baseline.
  - **Done when:** Plan is committed to the repository

- [ ] **[[Day 33 - Capstone (EDA)|Day 33 (Mon Nov 2)]]**: **Capstone (EDA)**
  - **Do:** Load the data, perform EDA, lock the target and metric (e.g. precision@50).
  - **Done when:** EDA notebook completed

- [ ] **[[Day 34 - Capstone (Baseline)|Day 34 (Tue Nov 3)]]**: **Capstone (Baseline)**
  - **Do:** Build a naive rule-based baseline and a reusable evaluation function.
  - **Done when:** You have a verifiable baseline number

- [ ] **[[Day 35 - Capstone (Grouped Splits)|Day 35 (Wed Nov 4)]]**: **Capstone (Grouped Splits)**
  - **Do:** Engineer features + implement a grouped validation split (split by client or domain).
  - **Done when:** Verified that no group appears in both train and test

- [ ] **[[Day 36 - Capstone (Models)|Day 36 (Thu Nov 5)]]**: **Capstone (Models)**
  - **Do:** Train Random Forest / XGBoost + hyperparameter tuning.
  - **Done when:** Beats the baseline on the grouped split

- [ ] **[[Day 37 - Capstone (Audit)|Day 37 (Fri Nov 6)]]**: **Capstone (Audit)**
  - **Do:** Leakage audit + error analysis: Where does the model fail, and why?
  - **Done when:** Written list of the top 3 failure patterns

- [ ] **[[Day 38 - Capstone (Reproducibility)|Day 38 (Sat Nov 7)]]**: **Capstone (Reproducibility)**
  - **Do:** Build recommendations layer + ensure reproducibility (pinned requirements, fixed seed, one-command run).
  - **Done when:** Notebook runs cleanly in a fresh Google Colab session

- [ ] **[[Day 39 - Review|Day 39 (Sun Nov 8)]]**: **Review**
  - **Do:** Re-run the whole capstone from a clean repository clone.
  - **Done when:** Completes without errors

- [ ] **[[Day 40 - Capstone ship (P1)|Day 40 (Mon Nov 9)]]**: **Capstone Ship (P1)**
  - **Do:** Write README (problem, approach, baseline vs model, limits) + presentation outline. Submit public link.
  - **Done when:** Project 1 (P1) submitted

- [ ] **[[Day 41 - Neural nets|Day 41 (Tue Nov 10)]]**: **Neural nets**
  - **Do:** 3Blue1Brown Neural Networks, ch 1–2.
  - **Done when:** Notes on neurons, weights, and loss documented

- [ ] **[[Day 42 - Backprop|Day 42 (Wed Nov 11)]]**: **Backprop**
  - **Do:** 3Blue1Brown Neural Networks, ch 3–4.
  - **Done when:** Backprop explained in your own words

- [ ] **[[Day 43 - micrograd (Part 1)|Day 43 (Thu Nov 12)]]**: **micrograd (1/2)**
  - **Do:** Karpathy "Building micrograd", first half, coding along.
  - **Done when:** `Value` class with `backward()` works

- [ ] **[[Day 44 - micrograd (Part 2)|Day 44 (Fri Nov 13)]]**: **micrograd (2/2)**
  - **Do:** Second half: Neuron, Layer, MLP, training loop.
  - **Done when:** Your MLP's loss demonstrably goes down

- [ ] **[[Day 45 - Buffer|Day 45 (Sat Nov 14)]]**: **Buffer / PyTorch Intro**
  - **Do:** Capstone revisions if reviewer requested changes. If not, PyTorch "Tensors" + "Datasets & DataLoaders".
  - **Done when:** Revisions resubmitted, or tutorial done

- [ ] **[[Day 46 - Review|Day 46 (Sun Nov 15)]]**: **Review**
  - **Do:** Rebuild micrograd's `backward()` from blank.
  - **Done when:** Post #5: Capstone results published

- [ ] **[[Day 47 - PyTorch (Part 1)|Day 47 (Mon Nov 16)]]**: **PyTorch (1/2)**
  - **Do:** [Learn the Basics](https://pytorch.org/tutorials/beginner/basics/intro.html): Tensors, data, build model.
  - **Done when:** Tutorial notebook completed

- [ ] **[[Day 48 - PyTorch (Part 2)|Day 48 (Tue Nov 17)]]**: **PyTorch (2/2)**
  - **Do:** Autograd, optimization loop, model save/load.
  - **Done when:** FashionMNIST model achieves above 85% accuracy

- [ ] **[[Day 49 - makemore 1 (Part 1)|Day 49 (Wed Nov 18)]]**: **makemore 1 (1/2)**
  - **Do:** Karpathy makemore part 1 (bigram), first half.
  - **Done when:** Counting bigram model implemented

- [ ] **[[Day 50 - makemore 1 (Part 2)|Day 50 (Thu Nov 19)]]**: **makemore 1 (2/2)**
  - **Do:** Second half: The neural-net version of the bigram.
  - **Done when:** Loss matches the counting model

- [ ] **[[Day 51 - makemore 2 (Part 1)|Day 51 (Fri Nov 20)]]**: **makemore 2 (1/2)**
  - **Do:** Karpathy makemore part 2 (MLP), first half.
  - **Done when:** Embedding + hidden layer built

- [ ] **[[Day 52 - makemore 2 (Part 2)|Day 52 (Sat Nov 21)]]**: **makemore 2 (2/2)**
  - **Do:** Second half: Train/dev/test split, tuning.
  - **Done when:** Generates plausible character/name sequences

- [ ] **[[Day 53 - Review|Day 53 (Sun Nov 22)]]**: **Review**
  - **Do:** Rebuild the PyTorch training loop from blank.
  - **Done when:** Post #6 is published

- [ ] **[[Day 54 - Transfer learning|Day 54 (Mon Nov 23)]]**: **Transfer learning**
  - **Do:** [fast.ai](https://course.fast.ai/) Lesson 1 on a Kaggle GPU.
  - **Done when:** Your own image classifier is trained and evaluated

- [ ] **[[Day 55 - CNNs|Day 55 (Tue Nov 24)]]**: **CNNs**
  - **Do:** StatQuest "Neural Networks Part 8: Image Classification with CNNs". Build a CNN in PyTorch on CIFAR-10.
  - **Done when:** Beats the MLP baseline

- [ ] **[[Day 56 - Deploy a model|Day 56 (Wed Nov 25)]]**: **Deploy a model**
  - **Do:** fast.ai Lesson 2: Gradio + Hugging Face Spaces.
  - **Done when:** Your first live model URL is functional

- [ ] **[[Day 57 - Attention|Day 57 (Thu Nov 26)]]**: **Attention**
  - **Do:** 3Blue1Brown Neural Networks, ch 5–6 (transformers, attention).
  - **Done when:** Attention mechanism sketched out on paper/canvas

- [ ] **[[Day 58 - Transformer architecture|Day 58 (Fri Nov 27)]]**: **Transformer architecture**
  - **Do:** [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/).
  - **Done when:** Architecture diagram redrawn from memory

- [ ] **[[Day 59 - GPT (Part 1)|Day 59 (Sat Nov 28)]]**: **GPT (1/2)**
  - **Do:** Karpathy "Let's build GPT", up to self-attention.
  - **Done when:** Self-attention head working in code

- [ ] **[[Day 60 - Review|Day 60 (Sun Nov 29)]]**: **Review**
  - **Do:** Rebuild self-attention head from a blank file.
  - **Done when:** Post #7 is published

- [ ] **[[Day 61 - GPT (Part 2) (Gate 2)|Day 61 (Mon Nov 30)]]**: **GPT (2/2) (Gate 2)**
  - **Do:** Finish "Let's build GPT": Multi-head attention, residual blocks, training loop.
  - **Done when:** **Gate 2:** Capstone in, tiny GPT trained

---

## 📅 Phase 3 — December: LLM Engineering, Deployment, Job Launch (Days 62–92)

**Monthly Goal:** Ship a RAG app with measured quality and a fine-tuned model behind an API, then spend the last week getting in front of employers.

- [ ] **[[Day 62 - Hugging Face|Day 62 (Tue Dec 1)]]**: **Hugging Face**
  - **Do:** [LLM Course](https://huggingface.co/learn/llm-course), ch 1–2 (pipelines, tokenizers, models).
  - **Done when:** Tokenize and run inference on 3 models

- [ ] **[[Day 63 - Fine-tune an encoder|Day 63 (Wed Dec 2)]]**: **Fine-tune an encoder**
  - **Do:** LLM Course ch 3: Fine-tune a BERT-style model for text classification (e.g. search-query intent).
  - **Done when:** Evaluation F1 score achieved and logged

- [ ] **[[Day 64 - LLM APIs + prompting|Day 64 (Thu Dec 3)]]**: **LLM APIs + prompting**
  - **Do:** [Anthropic prompt engineering guide](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview). Use a free-tier API to extract structured JSON from 50 texts.
  - **Done when:** At least 45/50 outputs parse cleanly

- [ ] **[[Day 65 - Vector search|Day 65 (Fri Dec 4)]]**: **Vector search**
  - **Do:** [Patterns for LLM systems](https://eugeneyan.com/writing/llm-patterns/) (RAG section). Chunk a corpus and index it in Chroma or pgvector.
  - **Done when:** Top-5 retrieval works accurately

- [ ] **[[Day 66 - P2 RAG v1|Day 66 (Sat Dec 5)]]**: **P2: RAG v1**
  - **Do:** Answer questions over a real corpus with citations (suggested: creator-community FAQs or docs).
  - **Done when:** RAG v1 works locally

- [ ] **[[Day 67 - Review|Day 67 (Sun Dec 6)]]**: **Review**
  - **Do:** Rebuild the Day 65 chunk → embed → retrieve pipeline from blank.
  - **Done when:** Post #8 is published

- [ ] **[[Day 68 - Evals|Day 68 (Mon Dec 7)]]**: **Evals**
  - **Do:** [Your AI Product Needs Evals](https://hamel.dev/blog/posts/evals/). Write 30 test questions. Measure retrieval hit rate and answer correctness (LLM-as-judge + spot checks).
  - **Done when:** Baseline eval scores recorded

- [ ] **[[Day 69 - Improve RAG|Day 69 (Tue Dec 8)]]**: **Improve RAG**
  - **Do:** Implement hybrid search (BM25 + vectors) + cross-encoder reranker from sbert.net.
  - **Done when:** Evaluation scores beat the v1 baseline

- [ ] **[[Day 70 - Tool use|Day 70 (Wed Dec 9)]]**: **Tool use**
  - **Do:** [Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents). Add one tool-calling step to P2.
  - **Done when:** Tool call runs end-to-end successfully

- [ ] **[[Day 71 - P2 ship|Day 71 (Thu Dec 10)]]**: **P2 Ship**
  - **Do:** Gradio UI → Hugging Face Spaces. README with before/after eval numbers.
  - **Done when:** P2 is live and accessible online

- [ ] **[[Day 72 - Fine-tuning theory|Day 72 (Fri Dec 11)]]**: **Fine-tuning theory**
  - **Do:** PEFT docs, LoRA conceptual guide. When to prompt vs RAG vs fine-tune.
  - **Done when:** One-page decision note written

- [ ] **[[Day 73 - P3 LoRA (Part 1)|Day 73 (Sat Dec 12)]]**: **P3: LoRA (1/2)**
  - **Do:** [Unsloth](https://docs.unsloth.ai/) Colab notebook: LoRA fine-tune a ~1B model on a narrow task.
  - **Done when:** Training completes successfully

- [ ] **[[Day 74 - Review|Day 74 (Sun Dec 13)]]**: **Review**
  - **Do:** Rebuild the P2 eval harness from blank.
  - **Done when:** Post #9: P2 eval results published

- [ ] **[[Day 75 - P3 LoRA (Part 2)|Day 75 (Mon Dec 14)]]**: **P3: LoRA (2/2)**
  - **Do:** Compare base, prompted, and fine-tuned models on held-out data. Push adapter to Hugging Face Hub.
  - **Done when:** Comparison table included in README

- [ ] **[[Day 76 - Serving|Day 76 (Tue Dec 15)]]**: **Serving**
  - **Do:** [FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/). Put a `/predict` endpoint in front of P3 (or P1 if CPU-constrained).
  - **Done when:** Endpoint returns live predictions

- [ ] **[[Day 77 - Docker|Day 77 (Wed Dec 16)]]**: **Docker**
  - **Do:** [Docker Get Started](https://docs.docker.com/get-started/). Containerize the API.
  - **Done when:** `docker run` serves predictions locally

- [ ] **[[Day 78 - Experiment tracking|Day 78 (Thu Dec 17)]]**: **Experiment tracking**
  - **Do:** [MLflow](https://mlflow.org/docs/latest/) quickstart. Log your P1 runs.
  - **Done when:** Runs are comparable in the MLflow UI

- [ ] **[[Day 79 - Testing + CI|Day 79 (Fri Dec 18)]]**: **Testing + CI**
  - **Do:** [Made With ML](https://madewithml.com/) testing lessons. GitHub Actions runs test suite on every push.
  - **Done when:** Green CI badge achieved on GitHub

- [ ] **[[Day 80 - Monitoring|Day 80 (Sat Dec 19)]]**: **Monitoring**
  - **Do:** [Evidently](https://docs.evidentlyai.com/) quickstart. Build a drift report on P1 data.
  - **Done when:** Drift report is committed to the repository

- [ ] **[[Day 81 - Review|Day 81 (Sun Dec 20)]]**: **Review**
  - **Do:** Redeploy P2 from a clean repository clone.
  - **Done when:** Post #10 is published

- [ ] **[[Day 82 - System design (Part 1)|Day 82 (Mon Dec 21)]]**: **System design (1/2)**
  - **Do:** [CS329S](https://stanford-cs329s.github.io/) notes. Design a content-decay alerting system: Data, model, serving, monitoring.
  - **Done when:** 1-page design doc completed

- [ ] **[[Day 83 - System design (Part 2)|Day 83 (Tue Dec 22)]]**: **System design (2/2)**
  - **Do:** Design a RAG support bot for 10k creators covering latency, cost, and evals.
  - **Done when:** 1-page design doc completed

- [ ] **[[Day 84 - Portfolio|Day 84 (Wed Dec 23)]]**: **Portfolio**
  - **Do:** Polish each project README (problem, approach, metric, result, demo link, run instructions). Pin P1–P3 on GitHub.
  - **Done when:** 3 polished repositories pinned on your profile

- [ ] **[[Day 85 - Interview theory|Day 85 (Thu Dec 24)]]**: **Interview theory**
  - **Do:** [ML Interviews Book](https://huyenchip.com/ml-interviews-book/): Answer 20 ML fundamentals questions out loud.
  - **Done when:** 20 answers written down

- [ ] **[[Day 86 - Interview coding|Day 86 (Fri Dec 25)]]**: **Interview coding**
  - **Do:** From scratch in NumPy: kNN, k-means, logistic regression. Plus 3 pandas/SQL problems.
  - **Done when:** All 6 implementations pass unit tests

- [ ] **[[Day 87 - Long-form post|Day 87 (Sat Dec 26)]]**: **Long-form post**
  - **Do:** "90 days of ML": What you built, with links, architecture, and results.
  - **Done when:** Article published online

- [ ] **[[Day 88 - Review|Day 88 (Sun Dec 27)]]**: **Review**
  - **Do:** Record a 3-minute walkthrough video of each project (P1, P2, P3).
  - **Done when:** 3 walkthrough recordings ready

- [ ] **[[Day 89 - CV + LinkedIn|Day 89 (Mon Dec 28)]]**: **CV + LinkedIn**
  - **Do:** Rewrite FlyRank experience with concrete metrics (e.g. "2× lift over baseline"), add Featured projects and headline.
  - **Done when:** CV PDF generated + LinkedIn profile updated

- [ ] **[[Day 90 - Applications|Day 90 (Tue Dec 29)]]**: **Applications**
  - **Do:** Shortlist 30 roles (remote AI/ML engineer on [Wellfound](https://wellfound.com/) and [Work at a Startup](https://www.workatastartup.com/), plus Nigerian tech companies). Send 5 applications.
  - **Done when:** 5 applications sent

- [ ] **[[Day 91 - Applications|Day 91 (Wed Dec 30)]]**: **Applications**
  - **Do:** Send 5 more applications. Message 5 engineers at your target companies.
  - **Done when:** 10 cumulative applications sent + 5 outreach messages

- [ ] **[[Day 92 - Retro (Gate 3)|Day 92 (Thu Dec 31)]]**: **Retro (Gate 3)**
  - **Do:** Send 5 more applications. Write a Q1 2027 plan based on where you are weakest.
  - **Done when:** **Gate 3:** 15 total applications sent, P2 live, Q1 2027 plan completed

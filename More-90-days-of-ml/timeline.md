# More 90 Days of ML: Interactive Master Timeline & Checklist 🗓️

> [!TIP]
> This roadmap represents Days 93–182 (Phases 4, 5, and 6). Click any checkbox `- [ ]` to mark tasks complete in Obsidian.

---

## 🏆 Projects & Gates Overview

| Project | Proves | Ships |
| :--- | :--- | :--- |
| **P2+** | Your December RAG app rebuilt on AWS with Terraform and CI/CD | Jan 30 |
| **P5** | Learning-to-rank model for content or community feed ranking | Feb 13 |
| **P4** | Self-hosted open LLM service: vLLM, quantized, traced, guarded, load-tested | Feb 27 |
| **P6 (Flagship)** | An ML feature in Oryzon's product, used by real users, with monitoring & A/B test | Mar 20 |

### 🎯 Key Gates
- [ ] **Gate 4 (Jan 31):** P2 on AWS, GPT-2 trained
- [ ] **Gate 5 (Feb 28):** P4 load-tested, P5 shipped
- [ ] **Gate 6 (Mar 31):** P6 live, 2 PRs open, 15 applications sent

---

## 📅 Phase 4 — January: Depth, Cloud, Production Engineering (Days 93–123)

**Monthly Goal:** Understand training from the inside and be able to deploy anything you build on AWS with one command.

- [ ] **[[Day 93 - Retro + flagship brief|Day 93 (Fri Jan 1)]]**: **Retro + flagship brief**
  - **Do:** List your 3 weakest topics from Q4. Write a 1-page flagship brief for Oryzon: the user problem, the ML feature, the success metric.
  - **Done when:** Brief is committed

- [ ] **[[Day 94 - Matrix calculus|Day 94 (Sat Jan 2)]]**: **Matrix calculus**
  - **Do:** MML book ch 5.1–5.3 (gradients, partial derivatives).
  - **Done when:** Exercises done

- [ ] **[[Day 95 - Review|Day 95 (Sun Jan 3)]]**: **Review**
  - **Do:** Weekly template + DDIA ch 1.
  - **Done when:** Post published

- [ ] **[[Day 96 - Backprop, matrix form|Day 96 (Mon Jan 4)]]**: **Backprop, matrix form**
  - **Do:** MML ch 5.4–5.6. Derive the backward pass of a 2-layer MLP with matrices.
  - **Done when:** Your gradients match PyTorch autograd

- [ ] **[[Day 97 - Probability|Day 97 (Tue Jan 5)]]**: **Probability**
  - **Do:** MML ch 6.1–6.5 + Seeing Theory ch 1–3. Simulate each distribution in NumPy.
  - **Done when:** Simulation notebook completed

- [ ] **[[Day 98 - Estimation|Day 98 (Wed Jan 6)]]**: **Estimation**
  - **Do:** StatQuest 'Bootstrapping' + 'Confidence Intervals'. Bootstrap a CI for your P1 metric.
  - **Done when:** P1 README reports a CI

- [ ] **[[Day 99 - Hypothesis tests|Day 99 (Thu Jan 7)]]**: **Hypothesis tests**
  - **Do:** StatQuest 'p-values' + 't-tests'. Read Evan Miller's A/B article. Simulate how peeking inflates false positives.
  - **Done when:** False-positive rate plot

- [ ] **[[Day 100 - Experiment design|Day 100 (Fri Jan 8)]]**: **Experiment design**
  - **Do:** Power, sample size, minimum detectable effect. Size an A/B test for your flagship metric.
  - **Done when:** Sample size in the brief

- [ ] **[[Day 101 - SQL depth|Day 101 (Sat Jan 9)]]**: **SQL depth**
  - **Do:** Window functions + CTEs. 5 medium problems on DataLemur.
  - **Done when:** 5 solved

- [ ] **[[Day 102 - Review|Day 102 (Sun Jan 10)]]**: **Review**
  - **Do:** Rebuild the matrix backprop from blank + DDIA ch 2.
  - **Done when:** Post published

- [ ] **[[Day 103 - Tokenizers (Part 1)|Day 103 (Mon Jan 11)]]**: **Tokenizers (Part 1)**
  - **Do:** Karpathy 'Let's build the GPT Tokenizer', first half.
  - **Done when:** Byte-level encoding works

- [ ] **[[Day 104 - Tokenizers (Part 2)|Day 104 (Tue Jan 12)]]**: **Tokenizers (Part 2)**
  - **Do:** Second half: implement BPE training and encoding.
  - **Done when:** Output matches minbpe on a test string

- [ ] **[[Day 105 - GPT-2 (Part 1)|Day 105 (Wed Jan 13)]]**: **GPT-2 (Part 1)**
  - **Do:** Karpathy 'Let's reproduce GPT-2 (124M)': the model code + loading the HF weights.
  - **Done when:** Your model generates with the GPT-2 weights

- [ ] **[[Day 106 - GPT-2 (Part 2)|Day 106 (Thu Jan 14)]]**: **GPT-2 (Part 2)**
  - **Do:** Speed-ups: mixed precision, flash attention, torch.compile.
  - **Done when:** Tokens/sec before vs after, in a table

- [ ] **[[Day 107 - GPT-2 (Part 3)|Day 107 (Fri Jan 15)]]**: **GPT-2 (Part 3)**
  - **Do:** LR schedule, weight decay, gradient accumulation.
  - **Done when:** Training loop matches the video

- [ ] **[[Day 108 - Scaled-down run|Day 108 (Sat Jan 16)]]**: **Scaled-down run**
  - **Do:** Train a small GPT on a Kaggle GPU for 1–2 h. (The full 124M run needs rented multi-GPU hardware, so it isn't the goal.)
  - **Done when:** Loss curve + samples in the README

- [ ] **[[Day 109 - Review|Day 109 (Sun Jan 17)]]**: **Review**
  - **Do:** Rebuild BPE from blank + DDIA ch 3.
  - **Done when:** Post published

- [ ] **[[Day 110 - AWS basics|Day 110 (Mon Jan 18)]]**: **AWS basics**
  - **Do:** IAM, S3, EC2 in AWS Skill Builder. Set a billing alarm first.
  - **Done when:** Alarm set, IAM user with MFA

- [ ] **[[Day 111 - Containers on AWS|Day 111 (Tue Jan 19)]]**: **Containers on AWS**
  - **Do:** Push the P3 image to ECR and run it on ECS Fargate or App Runner.
  - **Done when:** Public endpoint answers

- [ ] **[[Day 112 - Terraform|Day 112 (Wed Jan 20)]]**: **Terraform**
  - **Do:** HashiCorp 'Get Started – AWS' tutorial.
  - **Done when:** Resources created and destroyed cleanly

- [ ] **[[Day 113 - IaC for P2|Day 113 (Thu Jan 21)]]**: **IaC for P2**
  - **Do:** Write Terraform for P2: registry, service, secrets.
  - **Done when:** terraform apply brings P2 up

- [ ] **[[Day 114 - CI-CD|Day 114 (Fri Jan 22)]]**: **CI-CD**
  - **Do:** GitHub Actions: build -> push to ECR -> deploy on every merge to main.
  - **Done when:** A merge redeploys automatically

- [ ] **[[Day 115 - Managed vector store|Day 115 (Sat Jan 23)]]**: **Managed vector store**
  - **Do:** Move P2's vectors into managed Postgres with pgvector.
  - **Done when:** P2 evals still pass

- [ ] **[[Day 116 - Review|Day 116 (Sun Jan 24)]]**: **Review**
  - **Do:** Tear P2 down and bring it back up from Terraform + DDIA ch 4.
  - **Done when:** Post published

- [ ] **[[Day 117 - Pipelines|Day 117 (Mon Jan 25)]]**: **Pipelines**
  - **Do:** Prefect: a scheduled flow that ingests and re-indexes P2's corpus.
  - **Done when:** Flow runs on a schedule

- [ ] **[[Day 118 - Data quality|Day 118 (Tue Jan 26)]]**: **Data quality**
  - **Do:** Add schema and value checks (pandera) to the flow.
  - **Done when:** Bad data fails the run loudly

- [ ] **[[Day 119 - Monitoring|Day 119 (Wed Jan 27)]]**: **Monitoring**
  - **Do:** CloudWatch: latency, error-rate and cost dashboards, plus an alarm.
  - **Done when:** Dashboard screenshot in the README

- [ ] **[[Day 120 - Cost|Day 120 (Thu Jan 28)]]**: **Cost**
  - **Do:** Measure cost per 1,000 queries. Add response caching and re-measure.
  - **Done when:** Before/after cost in the README

- [ ] **[[Day 121 - Security|Day 121 (Fri Jan 29)]]**: **Security**
  - **Do:** Secrets Manager, least-privilege IAM, rate limiting.
  - **Done when:** No secrets in the repo, and limits enforced

- [ ] **[[Day 122 - P2+ ship|Day 122 (Sat Jan 30)]]**: **P2+ ship**
  - **Do:** Architecture diagram + a runbook (how to deploy, roll back, debug).
  - **Done when:** P2+ live on AWS

- [ ] **[[Day 123 - Review (Gate 4)|Day 123 (Sun Jan 31)]]**: **Review (Gate 4)**
  - **Do:** Gate 4 check + DDIA ch 5.
  - **Done when:** Gate 4: P2 on AWS, GPT-2 trained


---

## 📅 Phase 5 — February: Ranking, LLM Systems at Scale, Training Depth (Days 124–151)

**Monthly Goal:** Serve models under load, with measured latency, cost, quality and security.

- [ ] **[[Day 124 - Recsys basics|Day 124 (Mon Feb 1)]]**: **Recsys basics**
  - **Do:** Google Recommendation Systems course: candidate generation, content-based and collaborative filtering.
  - **Done when:** Course exercises completed

- [ ] **[[Day 125 - Retrieval models|Day 125 (Tue Feb 2)]]**: **Retrieval models**
  - **Do:** Matrix factorization on MovieLens, then read up on two-tower models.
  - **Done when:** MF model trained

- [ ] **[[Day 126 - Ranking metrics|Day 126 (Wed Feb 3)]]**: **Ranking metrics**
  - **Do:** Implement NDCG@k, MAP and MRR yourself.
  - **Done when:** Matches sklearn.metrics.ndcg_score

- [ ] **[[Day 127 - P5- learning to rank|Day 127 (Thu Feb 4)]]**: **P5: learning to rank**
  - **Do:** LightGBM LambdaRank on content-ranking data (search-style, or Oryzon feed data).
  - **Done when:** First ranker trained

- [ ] **[[Day 128 - P5 features + splits|Day 128 (Fri Feb 5)]]**: **P5 features + splits**
  - **Do:** Features + grouped splits. Compare against a popularity baseline.
  - **Done when:** Beats the baseline on NDCG@10

- [ ] **[[Day 129 - P5 online metric|Day 129 (Sat Feb 6)]]**: **P5 online metric**
  - **Do:** From offline to online: define the online metric and an A/B plan.
  - **Done when:** Plan in the README

- [ ] **[[Day 130 - Review|Day 130 (Sun Feb 7)]]**: **Review**
  - **Do:** Rebuild NDCG from blank + DDIA ch 6.
  - **Done when:** Post published

- [ ] **[[Day 131 - P5 serving|Day 131 (Mon Feb 8)]]**: **P5 serving**
  - **Do:** FastAPI endpoint with a latency budget. Measure p50/p95.
  - **Done when:** p95 under 100 ms locally

- [ ] **[[Day 132 - P5 features|Day 132 (Tue Feb 9)]]**: **P5 features**
  - **Do:** Batch vs real-time features, and feature caching.
  - **Done when:** Cached features in the serving path

- [ ] **[[Day 133 - P5 failure modes|Day 133 (Wed Feb 10)]]**: **P5 failure modes**
  - **Do:** Cold start, popularity bias, feedback loops. Add a cold-start fallback.
  - **Done when:** Fallback tested

- [ ] **[[Day 134 - Inference theory|Day 134 (Thu Feb 11)]]**: **Inference theory**
  - **Do:** Lilian Weng: Inference Optimization: KV cache, batching, quantization.
  - **Done when:** Notes: where memory and latency go

- [ ] **[[Day 135 - Quantization|Day 135 (Fri Feb 12)]]**: **Quantization**
  - **Do:** 4-bit quantize a 1–3B model. Measure memory, latency and quality against fp16.
  - **Done when:** 3-way comparison table

- [ ] **[[Day 136 - P5 ship|Day 136 (Sat Feb 13)]]**: **P5 ship**
  - **Do:** README: offline metrics vs baseline, latency, A/B plan.
  - **Done when:** P5 shipped

- [ ] **[[Day 137 - Review|Day 137 (Sun Feb 14)]]**: **Review**
  - **Do:** Rebuild the LambdaRank training loop from blank + DDIA ch 7.
  - **Done when:** Post published

- [ ] **[[Day 138 - P4- vLLM|Day 138 (Mon Feb 15)]]**: **P4: vLLM**
  - **Do:** vLLM quickstart: serve an open 1–3B model behind an OpenAI-compatible API.
  - **Done when:** Endpoint answers

- [ ] **[[Day 139 - P4- load test|Day 139 (Tue Feb 16)]]**: **P4: load test**
  - **Do:** Locust at 1, 5 and 20 concurrent users. Record tokens/sec and p95.
  - **Done when:** Throughput table

- [ ] **[[Day 140 - P4- observability|Day 140 (Wed Feb 17)]]**: **P4: observability**
  - **Do:** Langfuse traces on every request: prompt, latency, cost.
  - **Done when:** Traces visible in the dashboard

- [ ] **[[Day 141 - LLM security|Day 141 (Thu Feb 18)]]**: **LLM security**
  - **Do:** OWASP Top 10 for LLMs. Red-team P2 for prompt injection and data leaks.
  - **Done when:** 10 attacks logged, with results

- [ ] **[[Day 142 - Guardrails|Day 142 (Fri Feb 19)]]**: **Guardrails**
  - **Do:** Input/output filtering + structured-output validation. Re-run the red-team.
  - **Done when:** Fewer attacks succeed, and you've recorded how many

- [ ] **[[Day 143 - Evals in CI|Day 143 (Sat Feb 20)]]**: **Evals in CI**
  - **Do:** The eval suite runs on every PR and fails the PR on regression.
  - **Done when:** A deliberately bad PR goes red

- [ ] **[[Day 144 - Review|Day 144 (Sun Feb 21)]]**: **Review**
  - **Do:** Rebuild the Locust test from blank + DDIA ch 8.
  - **Done when:** Post published

- [ ] **[[Day 145 - Distributed training|Day 145 (Mon Feb 22)]]**: **Distributed training**
  - **Do:** PyTorch DDP tutorial. Run it on Kaggle's 2×T4.
  - **Done when:** Speed-up vs 1 GPU measured

- [ ] **[[Day 146 - Memory math|Day 146 (Tue Feb 23)]]**: **Memory math**
  - **Do:** FSDP/ZeRO and mixed-precision concepts. Calculate the GPU memory needed to fully fine-tune vs LoRA a 7B model.
  - **Done when:** Worked calculation in LEARNING.md

- [ ] **[[Day 147 - Preference tuning|Day 147 (Wed Feb 24)]]**: **Preference tuning**
  - **Do:** DPO with TRL on a small model and dataset.
  - **Done when:** DPO run finishes

- [ ] **[[Day 148 - Compare SFT vs DPO|Day 148 (Thu Feb 25)]]**: **Compare SFT vs DPO**
  - **Do:** SFT vs DPO on held-out prompts: LLM judge + your own review of 20 outputs.
  - **Done when:** Comparison table

- [ ] **[[Day 149 - P4 hardening|Day 149 (Fri Feb 26)]]**: **P4 hardening**
  - **Do:** Fallback to a hosted API when self-hosted fails. Timeouts, retries, cold starts.
  - **Done when:** A killed server is handled gracefully

- [ ] **[[Day 150 - P4 ship|Day 150 (Sat Feb 27)]]**: **P4 ship**
  - **Do:** README: throughput, p95, cost per 1M tokens (self-hosted vs API), security results.
  - **Done when:** P4 shipped

- [ ] **[[Day 151 - Review (Gate 5)|Day 151 (Sun Feb 28)]]**: **Review (Gate 5)**
  - **Do:** Gate 5 check + DDIA ch 9.
  - **Done when:** Gate 5: P4 load-tested, P5 shipped


---

## 📅 Phase 6 — March: Flagship, Open Source, Senior-Track Job Search (Days 152–182)

**Monthly Goal:** Ship ML that real users depend on, show you can work in other people's codebases, and interview like someone who owns systems.

- [ ] **[[Day 152 - P6- design doc|Day 152 (Mon Mar 1)]]**: **P6: design doc**
  - **Do:** Context, goals and non-goals, alternatives, risks, metrics, rollout plan. Have your co-founder review it.
  - **Done when:** Doc approved

- [ ] **[[Day 153 - P6- instrumentation|Day 153 (Tue Mar 2)]]**: **P6: instrumentation**
  - **Do:** Log the product events the success metric needs.
  - **Done when:** Events land in the database

- [ ] **[[Day 154 - P6- model v1|Day 154 (Wed Mar 3)]]**: **P6: model v1**
  - **Do:** Build on P2/P5 components.
  - **Done when:** Offline evals pass the bar in the design doc

- [ ] **[[Day 155 - P6- integration|Day 155 (Thu Mar 4)]]**: **P6: integration**
  - **Do:** Wire the model into the product behind a feature flag.
  - **Done when:** Works in staging

- [ ] **[[Day 156 - P6- launch checklist|Day 156 (Fri Mar 5)]]**: **P6: launch checklist**
  - **Do:** Rollback path, dashboards, alerts, on-call notes.
  - **Done when:** Checklist complete

- [ ] **[[Day 157 - P6- launch|Day 157 (Sat Mar 6)]]**: **P6: launch**
  - **Do:** Release to about 10% of users as an A/B test.
  - **Done when:** Real users are on it

- [ ] **[[Day 158 - Review|Day 158 (Sun Mar 7)]]**: **Review**
  - **Do:** Read every P6 log and error from the first 24 h + DDIA ch 10.
  - **Done when:** Issue list documented

- [ ] **[[Day 159 - Open source|Day 159 (Mon Mar 8)]]**: **Open source**
  - **Do:** Pick 2 good-first-issues in transformers, sentence-transformers, vLLM or scikit-learn. Read CONTRIBUTING.md.
  - **Done when:** 2 issues claimed

- [ ] **[[Day 160 - OSS PR #1 (Fix)|Day 160 (Tue Mar 9)]]**: **OSS PR #1 (Fix)**
  - **Do:** Reproduce the issue, write the fix and a test.
  - **Done when:** Tests pass locally

- [ ] **[[Day 161 - OSS PR #1 (Open)|Day 161 (Wed Mar 10)]]**: **OSS PR #1 (Open)**
  - **Do:** Open the PR with a clear description.
  - **Done when:** PR #1 open

- [ ] **[[Day 162 - P6- operate|Day 162 (Thu Mar 11)]]**: **P6: operate**
  - **Do:** Fix issues users hit and keep an incident log.
  - **Done when:** Log updated

- [ ] **[[Day 163 - OSS PR #2 (Fix)|Day 163 (Fri Mar 12)]]**: **OSS PR #2 (Fix)**
  - **Do:** Reproduce, fix, test.
  - **Done when:** Tests pass locally

- [ ] **[[Day 164 - OSS PR #2 (Open)|Day 164 (Sat Mar 13)]]**: **OSS PR #2 (Open)**
  - **Do:** Open the PR and respond to review comments on #1.
  - **Done when:** PR #2 open

- [ ] **[[Day 165 - Review|Day 165 (Sun Mar 14)]]**: **Review**
  - **Do:** DDIA ch 11.
  - **Done when:** Post published

- [ ] **[[Day 166 - P6- analyze|Day 166 (Mon Mar 15)]]**: **P6: analyze**
  - **Do:** A/B results: effect size, confidence interval, guardrail metrics.
  - **Done when:** Results table

- [ ] **[[Day 167 - P6- decide|Day 167 (Tue Mar 16)]]**: **P6: decide**
  - **Do:** Roll out, iterate or roll back, based on the data. Write the decision down.
  - **Done when:** Decision note committed

- [ ] **[[Day 168 - P6- write-up|Day 168 (Wed Mar 17)]]**: **P6: write-up**
  - **Do:** Case study: problem, approach, impact in numbers, what broke.
  - **Done when:** Draft done

- [ ] **[[Day 169 - Deep-dive post|Day 169 (Thu Mar 18)]]**: **Deep-dive post**
  - **Do:** 'What self-hosting an LLM actually costs', using your P4 numbers.
  - **Done when:** Published

- [ ] **[[Day 170 - Leadership signal|Day 170 (Fri Mar 19)]]**: **Leadership signal**
  - **Do:** Pitch a talk or workshop to a local or online dev community about P6.
  - **Done when:** Pitch sent

- [ ] **[[Day 171 - P6 ship|Day 171 (Sat Mar 20)]]**: **P6 ship**
  - **Do:** Case study page + repo, or a private demo if the code must stay closed.
  - **Done when:** P6 shipped

- [ ] **[[Day 172 - Review|Day 172 (Sun Mar 21)]]**: **Review**
  - **Do:** DDIA ch 12 (you've now finished the book).
  - **Done when:** Post published

- [ ] **[[Day 173 - System design (Part 1)|Day 173 (Mon Mar 22)]]**: **System design (Part 1)**
  - **Do:** ML System Design Interview ch 1 framework. Design a video recommendation system.
  - **Done when:** 1-page design

- [ ] **[[Day 174 - System design (Part 2)|Day 174 (Tue Mar 23)]]**: **System design (Part 2)**
  - **Do:** Design a search ranking system.
  - **Done when:** 1-page design

- [ ] **[[Day 175 - System design (Part 3)|Day 175 (Wed Mar 24)]]**: **System design (Part 3)**
  - **Do:** Design an LLM support assistant for 1M requests a day: cost, latency, evals, safety.
  - **Done when:** 1-page design

- [ ] **[[Day 176 - Mock interview|Day 176 (Thu Mar 25)]]**: **Mock interview**
  - **Do:** 45-minute system design mock with a peer or Claude. Record it and critique it.
  - **Done when:** 3 fixes noted

- [ ] **[[Day 177 - Behavioral|Day 177 (Fri Mar 26)]]**: **Behavioral**
  - **Do:** 6 STAR stories: ownership, failure, conflict, tradeoff, leadership, impact.
  - **Done when:** Stories written

- [ ] **[[Day 178 - Coding|Day 178 (Sat Mar 27)]]**: **Coding**
  - **Do:** 3 LeetCode mediums + attention from scratch in NumPy.
  - **Done when:** All pass

- [ ] **[[Day 179 - Review|Day 179 (Sun Mar 28)]]**: **Review**
  - **Do:** Record a 5-minute walkthrough of P6.
  - **Done when:** Recording ready

- [ ] **[[Day 180 - CV v2 + targeting|Day 180 (Mon Mar 29)]]**: **CV v2 + targeting**
  - **Do:** Lead with P6's impact, P4's numbers and your open-source PRs. Shortlist 30 mid-level AI/ML engineer and founding-engineer roles. Send 5 applications.
  - **Done when:** 5 applications sent

- [ ] **[[Day 181 - Applications|Day 181 (Tue Mar 30)]]**: **Applications**
  - **Do:** Send 5 more + 5 referral requests.
  - **Done when:** 10 applications sent

- [ ] **[[Day 182 - Retro (Gate 6)|Day 182 (Wed Mar 31)]]**: **Retro (Gate 6)**
  - **Do:** Send 5 more. Write a 6-month retro and the next quarter's plan.
  - **Done when:** Gate 6: P6 live, 2 PRs open, 15 applications sent

---

## 🎯 Senior-Signal Checklist (Target: All Ticked by Mar 31)

- [ ] **Ownership:** P6 is live with real users, and you can quote its impact and its failures
- [ ] **Judgement:** A design doc and a data-backed rollout decision for P6
- [ ] **Production:** P2+ can be rebuilt from Terraform, with CI/CD, monitoring, alarms and a runbook
- [ ] **Scale and Cost:** P4 throughput, p95 latency and cost per 1M tokens, measured
- [ ] **Security:** A red-team log plus working guardrails
- [ ] **Depth:** You can derive backprop in matrix form, explain KV caching and quantization, and size GPU memory for fine-tuning
- [ ] **Breadth:** You've shipped ranking (P5), retrieval (P2) and generation (P4)
- [ ] **Collaboration:** 2 open-source PRs opened
- [ ] **Communication:** 3 system design write-ups, a case study, a deep-dive post, a talk pitch
- [ ] **Applications:** 15 targeted applications and 5 referral requests sent

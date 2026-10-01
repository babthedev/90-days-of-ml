# More 90 Days of ML: Learning Log & Worked Calculations 📝

**Start Date:** 2027-01-01  
**Target Completion Date:** 2027-03-31  

---

## 💡 Key Calculations & Reflection Documents

### Day 146: GPU Memory Math
*Formula and worked calculation for GPU memory needed to fully fine-tune vs LoRA a 7B model:*
- **Model Parameters:** 7 Billion
- **Full Fine-Tuning Memory:**
  - Model weights (fp16 / bf16): 14 GB
  - Optimizer states (AdamW: fp32 momentum + variance): 28 GB
  - Gradients (fp16 / fp32): 14–28 GB
  - Activations & overhead: ~20–40 GB
  - **Total needed:** ~80–120 GB VRAM (requires multi-GPU / ZeRO-3 / FSDP)
- **LoRA Memory:**
  - Base model weights (frozen 4-bit / 8-bit / 16-bit): ~4–14 GB
  - LoRA trainable weights (e.g., r=16, alpha=32: < 1% params): ~0.1 GB
  - Optimizer states for LoRA only: ~0.4 GB
  - Activations: ~4–8 GB
  - **Total needed:** ~10–18 GB VRAM (fits on single consumer GPU e.g. RTX 3090/4090 or T4/A10G)

---

### Day 167: P6 Rollout Decision Note
*(To be recorded on Day 167: Data-backed rollout, iteration, or rollback decision)*

---

### Day 169: Self-Hosting LLM Cost Analysis
*(To be recorded on Day 169: Cost comparison of self-hosted vLLM vs hosted API based on P4 benchmark numbers)*

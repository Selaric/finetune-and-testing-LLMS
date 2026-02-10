
---

## Current Status
- ✅ Fine-tuned TinyLlama on HH-RLHF  
- ✅ Alignment-focused evaluation pipeline implemented  
- ✅ Model packaged and reproducible  

---

## Future Work
- Extend evaluation to power-seeking and deceptive framing
- Compare against RLAIF-trained public models
- Add automated CI evaluation for regression detection
- Scale experiments to additional base models (Phi-2, Qwen)

---

## Why This Matters
Most alignment research focuses on large, expensive models. This project demonstrates that **alignment failures like sycophancy are measurable and reducible in small models**, using principled datasets and evaluation.

Designed for:
- Alignment research
- Safety-focused ML engineering
- Pre-deployment model audits

---

## References
- Anthropic — *Training a Helpful and Harmless Assistant with RLHF*  
- Anthropic — *Measuring Model Alignment and Sycophancy*  
- Bai et al., 2022 — *Constitutional AI*

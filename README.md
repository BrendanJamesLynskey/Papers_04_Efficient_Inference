# Papers 04 — Efficient Inference & Serving

A single-page HTML presentation indexing the five publications that define the modern LLM inference and serving stack. It covers **FlashAttention** (Dao et al., 2022) and its IO-aware tiling plus online softmax that make attention exact yet memory-linear; **Switch Transformers** (Fedus et al., 2021) and sparse top-1 Mixture-of-Experts routing that decouples parameter count from per-token FLOPs; **GPTQ** (Frantar et al., 2022) for accurate one-shot 3–4 bit post-training quantisation (with AWQ as the activation-aware complement); **PagedAttention / vLLM** (Kwon et al., 2023) which manages the KV cache like OS virtual memory to eliminate fragmentation and multiply throughput; and **Speculative Decoding** (Leviathan et al., 2022/2023) which trades sequential latency for cheap parallel verification with a provably identical output distribution. Each slide gives the authors, year, and arXiv id, states the problem and contribution, explains why it matters to a practising engineer, and includes inline diagrams, flows, and comparison tables. Styled to match the Key LLM Publications series.

**Live site:** https://brendanjameslynskey.github.io/Papers_04_Efficient_Inference/

Part of the [Key LLM Publications sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_Key_Publications)

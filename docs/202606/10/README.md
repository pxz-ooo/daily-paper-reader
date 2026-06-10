# 日报 · 2026-06-10

- 生成时间：2026-06-10 22:47:05 UTC
- 当次推荐总数：17
- 精读区：6
- 速读区：11

## 今日简报（AI）
今日精选17篇论文，精读6篇，重点攻克混合专家推理的CPU-GPU混合架构与长上下文扩散模型的预测预填充方案。  
最值得关注的是两项高分工作：本地MoE推理通过CPU-GPU协同达到云级SLO，以及扩散语言模型用预测性预填充突破长上下文瓶颈。  
普通读者可优先精读这两篇，并留意速读中关于KV缓存稀疏化、4比特量化和LoRA内存优化的实用技巧。

## 精读区
1. [Achieving Cloud-Grade SLOs for Local Mixture-of-Experts Inference through CPU-GPU Hybrid Design](/202606/10/2606.10493v1-achieving-cloud-grade-slos-for-local-mixture-of-experts-inference-through-cpu-gpu-hybrid-design) （9.0/10）
2. [Prefilling-dLLM: Predictive Prefilling for Long-Context Inference in Diffusion Language Models](/202606/10/2606.10537v1-prefilling-dllm-predictive-prefilling-for-long-context-inference-in-diffusion-language-models) （9.0/10）
3. [K-Forcing: Joint Next-K-Token Decoding via Push-Forward Language Modeling](/202606/10/2606.10820v1-k-forcing-joint-next-k-token-decoding-via-push-forward-language-modeling) （9.0/10）
4. [CLP: Collocation-Length Prediction for Zero-Loss Adaptive Multi-Token Inference](/202606/10/2606.10935v1-clp-collocation-length-prediction-for-zero-loss-adaptive-multi-token-inference) （9.0/10）
5. [Express Language Modeling](/202606/10/2606.10944v1-express-language-modeling) （9.0/10）
6. [SAID: Accelerating Diffusion-Based Language Models via Scaffold-Aware Iterative Decoding](/202606/10/2606.04974v1-said-accelerating-diffusion-based-language-models-via-scaffold-aware-iterative-decoding) （8.0/10）

## 速读区
1. [Augmenting Attention with Exponentially Decaying Memory Improves Query-Aware KV Sparsity](/202606/10/2605.28640v1-augmenting-attention-with-exponentially-decaying-memory-improves-query-aware-kv-sparsity) （8.0/10）
2. [TwinQuant: Learnable Subspace Decomposition for 4-Bit LLM Quantization](/202606/10/2606.01556v1-twinquant-learnable-subspace-decomposition-for-4-bit-llm-quantization) （8.0/10）
3. [Rethinking LoRA Memory Through the Lens of KV Cache Compression](/202606/10/2606.05698v1-rethinking-lora-memory-through-the-lens-of-kv-cache-compression) （8.0/10）
4. [FlashMemory-DeepSeek-V4: Lightning Index Ultra-Long Context via Lookahead Sparse Attention](/202606/10/2606.09079v2-flashmemory-deepseek-v4-lightning-index-ultra-long-context-via-lookahead-sparse-attention) （8.0/10）
5. [UniSVQ: 2-bit Unified Scalar-Vector Quantization](/202606/10/2606.10520v1-unisvq-2-bit-unified-scalar-vector-quantization) （8.0/10）
6. [Supportive Token Revealing for Fast Diffusion Language Model Decoding](/202606/10/2606.04236v1-supportive-token-revealing-for-fast-diffusion-language-model-decoding) （7.0/10）
7. [Recover-LoRA for Aggressive Quantization: Reclaiming Accuracy in 2-Bit Language Models via Low-Rank Adaptation with Knowledge Distillation on Synthetic Data](/202606/10/2606.04238v1-recover-lora-for-aggressive-quantization-reclaiming-accuracy-in-2-bit-language-models-via-low-rank-adaptation-with-knowledge-distillation-on-synthetic-data) （7.0/10）
8. [STaR-Quant: State-Time Consistent Post-Training Quantization for Diffusion Large Language Models](/202606/10/2606.04945v1-star-quant-state-time-consistent-post-training-quantization-for-diffusion-large-language-models) （7.0/10）
9. [STaR-Quant: State-Time Consistent Post-Training Quantization for Diffusion Large Language Models](/202606/10/2606.04945v2-star-quant-state-time-consistent-post-training-quantization-for-diffusion-large-language-models) （7.0/10）
10. [Parallel Causal Associative Fields: Gated Sparse Memory for Long-Context Language Modeling](/202606/10/2606.10435v1-parallel-causal-associative-fields-gated-sparse-memory-for-long-context-language-modeling) （6.0/10）
11. [Dynamic Linear Attention](/202606/10/2606.10650v1-dynamic-linear-attention) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。

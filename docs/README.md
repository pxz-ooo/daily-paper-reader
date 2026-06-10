<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-10
- 运行时间：2026-06-10 22:47:05 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日共推荐17篇论文，精读6篇、速读11篇，聚焦推理效率与模型压缩。重点看本地MoE推理的CPU-GPU混合设计与扩散语言模型预填充方法（均9.0分）。建议优先阅读这两篇高分论文，并留意KV缓存压缩方向（速读中三篇8.0分均涉及）。
- 详情：[/202606/10/README](/202606/10/README)

### 精读区论文标签
1. [Achieving Cloud-Grade SLOs for Local Mixture-of-Experts Inference through CPU-GPU Hybrid Design](/202606/10/2606.10493v1-achieving-cloud-grade-slos-for-local-mixture-of-experts-inference-through-cpu-gpu-hybrid-design)  
   标签：评分：9.0/10、query:inf-accel
   evidence：流式预加载预填充（SLP）提升预填充吞吐量
2. [Prefilling-dLLM: Predictive Prefilling for Long-Context Inference in Diffusion Language Models](/202606/10/2606.10537v1-prefilling-dllm-predictive-prefilling-for-long-context-inference-in-diffusion-language-models)  
   标签：评分：9.0/10、query:inf-accel
   evidence：通过分块KV缓存和稀疏预填充优化长上下文LLM推理中的预填充阶段
3. [K-Forcing: Joint Next-K-Token Decoding via Push-Forward Language Modeling](/202606/10/2606.10820v1-k-forcing-joint-next-k-token-decoding-via-push-forward-language-modeling)  
   标签：评分：9.0/10、query:inf-accel
   evidence：联合下一个k令牌解码实现加速
4. [CLP: Collocation-Length Prediction for Zero-Loss Adaptive Multi-Token Inference](/202606/10/2606.10935v1-clp-collocation-length-prediction-for-zero-loss-adaptive-multi-token-inference)  
   标签：评分：9.0/10、query:inf-accel
   evidence：零损失多令牌预测加速LLM解码
5. [Express Language Modeling](/202606/10/2606.10944v1-express-language-modeling)  
   标签：评分：9.0/10、query:inf-accel
   evidence：用于预填充、KV缓存压缩和解码加速的通用工具
6. [SAID: Accelerating Diffusion-Based Language Models via Scaffold-Aware Iterative Decoding](/202606/10/2606.04974v1-said-accelerating-diffusion-based-language-models-via-scaffold-aware-iterative-decoding)  
   标签：评分：8.0/10、query:inf-accel
   evidence：通过支架感知迭代解码重新分配令牌间计算以加速扩散语言模型解码

### 速读区论文标签
1. [Augmenting Attention with Exponentially Decaying Memory Improves Query-Aware KV Sparsity](/202606/10/2605.28640v1-augmenting-attention-with-exponentially-decaying-memory-improves-query-aware-kv-sparsity)  
   标签：评分：8.0/10、query:inf-accel
   evidence：增强查询感知KV稀疏性以提高推理效率
2. [TwinQuant: Learnable Subspace Decomposition for 4-Bit LLM Quantization](/202606/10/2606.01556v1-twinquant-learnable-subspace-decomposition-for-4-bit-llm-quantization)  
   标签：评分：8.0/10、query:inf-accel
   evidence：LLM推理的4比特量化以减少内存和延迟
3. [Rethinking LoRA Memory Through the Lens of KV Cache Compression](/202606/10/2606.05698v1-rethinking-lora-memory-through-the-lens-of-kv-cache-compression)  
   标签：评分：8.0/10、query:inf-accel
   evidence：KV缓存压缩与LoRA内存的交互研究
4. [FlashMemory-DeepSeek-V4: Lightning Index Ultra-Long Context via Lookahead Sparse Attention](/202606/10/2606.09079v2-flashmemory-deepseek-v4-lightning-index-ultra-long-context-via-lookahead-sparse-attention)  
   标签：评分：8.0/10、query:inf-accel
   evidence：提出前瞻稀疏注意力，通过主动保留仅查询关键块来减少KV缓存内存。
5. [UniSVQ: 2-bit Unified Scalar-Vector Quantization](/202606/10/2606.10520v1-unisvq-2-bit-unified-scalar-vector-quantization)  
   标签：评分：8.0/10、query:inf-accel
   evidence：2位统一标量-向量量化用于大模型推理加速
6. [Supportive Token Revealing for Fast Diffusion Language Model Decoding](/202606/10/2606.04236v1-supportive-token-revealing-for-fast-diffusion-language-model-decoding)  
   标签：评分：7.0/10、query:inf-accel
   evidence：通过支持性令牌揭示加速扩散语言模型解码
7. [Recover-LoRA for Aggressive Quantization: Reclaiming Accuracy in 2-Bit Language Models via Low-Rank Adaptation with Knowledge Distillation on Synthetic Data](/202606/10/2606.04238v1-recover-lora-for-aggressive-quantization-reclaiming-accuracy-in-2-bit-language-models-via-low-rank-adaptation-with-knowledge-distillation-on-synthetic-data)  
   标签：评分：7.0/10、query:inf-accel
   evidence：激进2比特量化提升LLM推理吞吐量
8. [STaR-Quant: State-Time Consistent Post-Training Quantization for Diffusion Large Language Models](/202606/10/2606.04945v1-star-quant-state-time-consistent-post-training-quantization-for-diffusion-large-language-models)  
   标签：评分：7.0/10、query:inf-accel
   evidence：面向扩散大语言模型的后训练量化加速推理
9. [STaR-Quant: State-Time Consistent Post-Training Quantization for Diffusion Large Language Models](/202606/10/2606.04945v2-star-quant-state-time-consistent-post-training-quantization-for-diffusion-large-language-models)  
   标签：评分：7.0/10、query:inf-accel
   evidence：扩散大模型量化加速推理
10. [Parallel Causal Associative Fields: Gated Sparse Memory for Long-Context Language Modeling](/202606/10/2606.10435v1-parallel-causal-associative-fields-gated-sparse-memory-for-long-context-language-modeling)  
   标签：评分：6.0/10、query:inf-accel
   evidence：面向长上下文的稀疏记忆机制用于高效推理
11. [Dynamic Linear Attention](/202606/10/2606.10650v1-dynamic-linear-attention)  
   标签：评分：6.0/10、query:inf-accel
   evidence：动态线性注意力降低LLM推理的二次复杂度


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

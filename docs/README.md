<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-11 ~ 2026-06-09
- 运行时间：2026-06-09 15:41:57 UTC
- 运行状态：成功
- 本次总论文数：25
- 精读区：14
- 速读区：11

### 今日简报（AI）
本期精选25篇论文，精读14篇、速读11篇，聚焦LLM推理加速与多token生成两大热点。

最值得关注的两个方向：CATS提出级联自适应树推测，突破内存受限下的LLM推理瓶颈；BitLM利用比特级连续扩散实现多token并行生成，显著提升效率。

建议普通读者重点跟进Cache压缩与推测解码技术，这将直接提升大模型在边缘设备上的实用性与响应速度。
- 详情：[/20260511-20260609/README](/20260511-20260609/README)

### 精读区论文标签
1. [CATS: Cascaded Adaptive Tree Speculation for Memory-Limited LLM Inference Acceleration](/20260511-20260609/2605.11186v1-cats-cascaded-adaptive-tree-speculation-for-memory-limited-llm-inference-acceleration)  
   标签：评分：9.0/10、query:inf-accel
   evidence：级联自适应树推测用于内存受限解码
2. [BitLM: Unlocking Multi-Token Language Generation with Bitwise Continuous Diffusion](/20260511-20260609/2605.11577v1-bitlm-unlocking-multi-token-language-generation-with-bitwise-continuous-diffusion)  
   标签：评分：9.0/10、query:inf-accel
   evidence：通过扩散实现多标记预测以加速解码
3. [Meta-Soft: Leveraging Composable Meta-Tokens for Context-Preserving KV Cache Compression](/20260511-20260609/2605.22337v1-meta-soft-leveraging-composable-meta-tokens-for-context-preserving-kv-cache-compression)  
   标签：评分：9.0/10、query:inf-accel
   evidence：面向长上下文LLM推理的KV缓存压缩
4. [Meta-Soft: Leveraging Composable Meta-Tokens for Context-Preserving KV Cache Compression](/20260511-20260609/2605.22337v2-meta-soft-leveraging-composable-meta-tokens-for-context-preserving-kv-cache-compression)  
   标签：评分：9.0/10、query:inf-accel
   evidence：基于探测驱动的元令牌的动态KV缓存压缩
5. [Adaptive Mass-Segmented KV Compression for Long-Context Reasoning](/20260511-20260609/2605.23200v1-adaptive-mass-segmented-kv-compression-for-long-context-reasoning)  
   标签：评分：9.0/10、query:inf-accel
   evidence：自适应KV缓存压缩用于长上下文推理
6. [A Simple Plug-in for Improving Eviction-Based KV Cache Compression](/20260511-20260609/2605.23258v1-a-simple-plug-in-for-improving-eviction-based-kv-cache-compression)  
   标签：评分：9.0/10、query:inf-accel
   evidence：通过三路令牌路由实现KV缓存压缩
7. [Pair-In, Pair-Out: Latent Multi-Token Prediction for Efficient LLMs](/20260511-20260609/2605.27255v1-pair-in-pair-out-latent-multi-token-prediction-for-efficient-llms)  
   标签：评分：9.0/10、query:inf-accel
   evidence：潜在多token预测提升LLM效率
8. [Hurwitz Quaternion Multiplicative Quantization for KV Cache Compression](/20260511-20260609/2605.27646v1-hurwitz-quaternion-multiplicative-quantization-for-kv-cache-compression)  
   标签：评分：9.0/10、query:inf-accel
   evidence：通过四元数量化压缩KV缓存
9. [Speculative Pipeline Decoding: Higher-Accruacy and Zero-Bubble Speculation via Pipeline Parallelism](/20260511-20260609/2605.30852v1-speculative-pipeline-decoding-higher-accruacy-and-zero-bubble-speculation-via-pipeline-parallelism)  
   标签：评分：9.0/10、query:inf-accel
   evidence：利用流水线并行进行投机流水线解码加速LLM推理
10. [GRKV: Global Regression for Training-Free KV Cache Compression in Long-Context LLMs](/20260511-20260609/2605.31105v1-grkv-global-regression-for-training-free-kv-cache-compression-in-long-context-llms)  
   标签：评分：9.0/10、query:inf-accel
   evidence：针对长上下文LLM的KV缓存压缩
11. [Multi-Segment Attention: Enabling Efficient KV-Cache Management for Faster Large Language Model Serving](/20260511-20260609/2606.02964v1-multi-segment-attention-enabling-efficient-kv-cache-management-for-faster-large-language-model-serving)  
   标签：评分：9.0/10、query:inf-accel
   evidence：面向计算延迟感知的大模型KV缓存管理
12. [D^2SD: Accelerating Speculative Decoding with Dual Diffusion Draft Models](/20260511-20260609/2606.04446v1-d2sd-accelerating-speculative-decoding-with-dual-diffusion-draft-models)  
   标签：评分：9.0/10、query:inf-accel
   evidence：使用双扩散草稿模型的投机解码，每验证步生成多个token
13. [Still: Amortized KV Cache Compaction in a Single Forward Pass](/20260511-20260609/2606.07878v1-still-amortized-kv-cache-compaction-in-a-single-forward-pass)  
   标签：评分：9.0/10、query:inf-accel
   evidence：通过Perceiver在单次前向传播中实现KV缓存压缩
14. [STAR-KV: Low-Rank KV Cache Compression via Soft Thresholding for Adaptive Rank Control](/20260511-20260609/2606.08382v1-star-kv-low-rank-kv-cache-compression-via-soft-thresholding-for-adaptive-rank-control)  
   标签：评分：9.0/10、query:inf-accel
   evidence：通过可微分阈值实现自适应低秩KV缓存压缩

### 速读区论文标签
1. [KVCapsule: Efficient Sequential KV Cache Compression for Vision-Language Models with Asymmetric Redundancy](/20260511-20260609/2605.16439v1-kvcapsule-efficient-sequential-kv-cache-compression-for-vision-language-models-with-asymmetric-redundancy)  
   标签：评分：8.0/10、query:inf-accel
   evidence：针对视觉语言模型的序列KV缓存压缩，利用不对称冗余
2. [VeriCache: Turning Lossy KV Cache into Lossless LLM Inference](/20260511-20260609/2605.17613v1-vericache-turning-lossy-kv-cache-into-lossless-llm-inference)  
   标签：评分：8.0/10、query:inf-accel
   evidence：使用压缩KV缓存草稿token，再用完整缓存验证，实现无损推理
3. [Block-Based Double Decoders](/20260511-20260609/2605.18807v1-block-based-double-decoders)  
   标签：评分：8.0/10、query:inf-accel
   evidence：将KV缓存内存和每token计算量减少至少2/3，且不牺牲预填充缓存
4. [SSV: Sparse Speculative Verification for Efficient LLM Inference](/20260511-20260609/2605.19893v2-ssv-sparse-speculative-verification-for-efficient-llm-inference)  
   标签：评分：8.0/10、query:inf-accel
   evidence：结合动态稀疏注意力和投机解码的稀疏投机验证
5. [Compute Where it Counts: Self Optimizing Language Models](/20260511-20260609/2605.10875v1-compute-where-it-counts-self-optimizing-language-models)  
   标签：评分：7.0/10、query:inf-accel
   evidence：解码阶段每token动态分配计算预算，控制注意力和激活稀疏性
6. [Full Attention Strikes Back: Transferring Full Attention into Sparse within Hundred Training Steps](/20260511-20260609/2605.16928v1-full-attention-strikes-back-transferring-full-attention-into-sparse-within-hundred-training-steps)  
   标签：评分：7.0/10、query:inf-accel
   evidence：将全注意力转换为稀疏注意力以加速长上下文推理
7. [Context Memorization for Efficient Long Context Generation](/20260511-20260609/2605.18226v1-context-memorization-for-efficient-long-context-generation)  
   标签：评分：7.0/10、query:inf-accel
   evidence：在长上下文生成中减少前缀内存的无训练方法
8. [CachePrune: Privacy-Aware and Fine-Grained KV Cache Sharing for Efficient LLM Inference](/20260511-20260609/2605.23640v1-cacheprune-privacy-aware-and-fine-grained-kv-cache-sharing-for-efficient-llm-inference)  
   标签：评分：7.0/10、query:inf-accel
   evidence：KV缓存共享减少内存与冗余计算
9. [Prune, Update and Trim: Robust Structured Pruning for Large Language Models](/20260511-20260609/2605.18331v1-prune-update-and-trim-robust-structured-pruning-for-large-language-models)  
   标签：评分：6.0/10、query:inf-accel
   evidence：结构化剪枝减少LLM参数量和推理成本
10. [A general tensor-structured compression scheme for efficient large language models](/20260511-20260609/2605.25344v1-a-general-tensor-structured-compression-scheme-for-efficient-large-language-models)  
   标签：评分：6.0/10、query:inf-accel
   evidence：张量结构化压缩替代稠密层，减少存储和计算开销
11. [PrunePath: Towards Highly Structured Sparse Language Models](/20260511-20260609/2605.28283v1-prunepath-towards-highly-structured-sparse-language-models)  
   标签：评分：6.0/10、query:inf-accel
   evidence：基于预算自适应的FFN层结构化稀疏化以提升推理效率


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

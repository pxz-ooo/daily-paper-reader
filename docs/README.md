<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-09
- 运行时间：2026-06-09 22:15:41 UTC
- 运行状态：成功
- 本次总论文数：20
- 精读区：9
- 速读区：11

### 今日简报（AI）
今日推荐阅读9篇精读论文，聚焦长上下文推理和检索增强生成优化。最值得关注的是MomentKV（9.0分）提出消除KV缓存驱逐中的方向性差距，以及LazyAttention（9.0分）通过延迟位置编码提升RAG效率。建议优先精读这两篇高评分论文，再速读速读列表中关于投机解码和向量量化的三篇8.0分工作以拓宽视野。
- 详情：[/202606/09/README](/202606/09/README)

### 精读区论文标签
1. [MomentKV: Closing the Directional Gap in KV Cache Eviction for Long-Context Inference](/202606/09/2606.01563v1-momentkv-closing-the-directional-gap-in-kv-cache-eviction-for-long-context-inference)  
   标签：评分：9.0/10、query:inf-accel
   evidence：KV缓存驱逐用于长上下文推理
2. [LazyAttention: Efficient Retrieval-Augmented Generation with Deferred Positional Encoding](/202606/09/2606.04302v1-lazyattention-efficient-retrieval-augmented-generation-with-deferred-positional-encoding)  
   标签：评分：9.0/10、query:inf-accel
   evidence：提出LazyAttention通过延迟位置编码实现零拷贝位置无关KV重用
3. [AdaPLD: Adaptive Retrieval and Reuse for Efficient Model-Free Speculative Decoding](/202606/09/2606.05742v1-adapld-adaptive-retrieval-and-reuse-for-efficient-model-free-speculative-decoding)  
   标签：评分：9.0/10、query:inf-accel
   evidence：无需草案模型的自适应检索与重用的推测解码
4. [QCFuse: Query-Aware Cache Fusion via Compressed View for Efficient RAG Serving](/202606/09/2606.05875v1-qcfuse-query-aware-cache-fusion-via-compressed-view-for-efficient-rag-serving)  
   标签：评分：9.0/10、query:inf-accel
   evidence：通过查询感知KV缓存融合优化RAG预填充阶段
5. [WhiFlash: Accelerating Speculative Decoding with Token-Level Cross-Paradigm Routing](/202606/09/2606.07710v1-whiflash-accelerating-speculative-decoding-with-token-level-cross-paradigm-routing)  
   标签：评分：9.0/10、query:inf-accel
   evidence：令牌级跨范式路由加速推测解码
6. [FlashMemory-DeepSeek-V4: Lightning Index Ultra-Long Context via Lookahead Sparse Attention](/202606/09/2606.09079v1-flashmemory-deepseek-v4-lightning-index-ultra-long-context-via-lookahead-sparse-attention)  
   标签：评分：9.0/10、query:inf-accel
   evidence：通过前瞻稀疏注意力压缩KV缓存
7. [Beyond FLOPs: Benchmarking Real Inference Acceleration of LLM Pruning under a GEMM-Centric Taxonomy](/202606/09/2606.09080v1-beyond-flops-benchmarking-real-inference-acceleration-of-llm-pruning-under-a-gemm-centric-taxonomy)  
   标签：评分：9.0/10、query:inf-accel
   evidence：在GEMM中心分类法下基准测试LLM剪枝的真实推理加速
8. [From Rigid to Dynamic: Entropy-Guided Adaptive Inference for Long-Context LLMs](/202606/09/2606.09508v1-from-rigid-to-dynamic-entropy-guided-adaptive-inference-for-long-context-llms)  
   标签：评分：9.0/10、query:inf-accel
   evidence：基于熵引导的自适应KV缓存压缩方法用于长上下文LLM推理
9. [End-to-End Context Compression at Scale](/202606/09/2606.09659v1-end-to-end-context-compression-at-scale)  
   标签：评分：9.0/10、query:inf-accel
   evidence：使用编码器-解码器压缩器大规模端到端上下文压缩减少KV缓存

### 速读区论文标签
1. [Draft Less, Retrieve More: Hybrid Tree Construction for Speculative Decoding](/202606/09/2605.20104v1-draft-less-retrieve-more-hybrid-tree-construction-for-speculative-decoding)  
   标签：评分：8.0/10、query:inf-accel
   evidence：推测解码的混合树构建
2. [EVA: Accelerating LLM Decoding via an Efficient Vector Quantization Architecture](/202606/09/2605.24144v1-eva-accelerating-llm-decoding-via-an-efficient-vector-quantization-architecture)  
   标签：评分：8.0/10、query:inf-accel
   evidence：权重量化加速解码阶段
3. [IndexMem: Learned KV-Cache Eviction with Latent Memory for Long-Context LLM Inference](/202606/09/2605.25475v1-indexmem-learned-kv-cache-eviction-with-latent-memory-for-long-context-llm-inference)  
   标签：评分：8.0/10、query:inf-accel
   evidence：学习KV重要度预测以逐出，潜记忆防止遗忘
4. [Cassandra: Enabling Reasoning LLMs at Edge via Self-Speculative Decoding](/202606/09/2605.26558v1-cassandra-enabling-reasoning-llms-at-edge-via-self-speculative-decoding)  
   标签：评分：8.0/10、query:inf-accel
   evidence：面向边缘设备的自推测解码
5. [LLM Compression with Jointly Optimizing Architectural and Quantization choices](/202606/09/2606.04063v1-llm-compression-with-jointly-optimizing-architectural-and-quantization-choices)  
   标签：评分：7.0/10、query:inf-accel
   evidence：大语言模型压缩以实现高效推理
6. [Minimizing the Hidden Cost of Scales: Graph-Guided Ultra-Low-Bit Quantization for Large Language Models](/202606/09/2606.05429v1-minimizing-the-hidden-cost-of-scales-graph-guided-ultra-low-bit-quantization-for-large-language-models)  
   标签：评分：7.0/10、query:inf-accel
   evidence：超低位量化加速大语言模型推理
7. [Beyond Greedy Chunking: SLO-Aware Sliding-Window Scheduling for LLM Inference](/202606/09/2606.05933v1-beyond-greedy-chunking-slo-aware-sliding-window-scheduling-for-llm-inference)  
   标签：评分：7.0/10、query:inf-accel
   evidence：面向服务等级协议的LLM推理调度加速
8. [OffQ: Taming Structured Outliers in LLM Quantization by Offsetting](/202606/09/2606.07116v1-offq-taming-structured-outliers-in-llm-quantization-by-offsetting)  
   标签：评分：7.0/10、query:inf-accel
   evidence：低比特量化加速LLM推理
9. [ProbeScale: Probing Analysis to Optimize Neural Scaling Laws for Efficient Small Language Model Inference](/202606/09/2606.01806v1-probescale-probing-analysis-to-optimize-neural-scaling-laws-for-efficient-small-language-model-inference)  
   标签：评分：6.0/10、query:inf-accel
   evidence：通过探针分析优化小语言模型推理效率
10. [Depth-Attention: Cross-Layer Value Mixing for Language Models](/202606/09/2606.05014v1-depth-attention-cross-layer-value-mixing-for-language-models)  
   标签：评分：6.0/10、query:inf-accel
   evidence：新的注意力机制跨层选择性混合值，是对标准注意力的改进，与FlashAttention和PagedAttention等注意力优化相关
11. [Skip a Layer or Loop It? Learning Program-of-Layers in LLMs](/202606/09/2606.06574v1-skip-a-layer-or-loop-it-learning-program-of-layers-in-llms)  
   标签：评分：6.0/10、query:inf-accel
   evidence：动态跳过或循环层实现高效LLM推理


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

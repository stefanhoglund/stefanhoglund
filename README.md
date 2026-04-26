# Stefan Höglund

Research engineer and systems builder completing an MSc in Applied Artificial Intelligence at Luleå University of Technology. I work at the intersection of mechanistic interpretability and ML systems infrastructure — specifically, how transformers encode task-relevant structure internally, and how to build the tooling that makes that kind of research tractable at scale.

## Research

**Layer 0 attention dominance in transformer task-type encoding**
Across two independent experiments on GPT-2-small and Llama 3 8B, I found that Layer 0 attention features dominate task-type classification at 73.3% accuracy — contrary to the conventional assumption that later layers carry more task-specific information. The consistency across a 68x difference in model scale suggests this may be a structural property of transformer attention independent of scale.

- [Thesis: Mechanistic Interpretability of NL-to-SQL Systems](https://github.com/your-handle/thesis-repo) — TransformerLens analysis of Llama 3 8B, governed semantic layer, empirical failure mode taxonomy
- [GPT-2 Attention Pattern Study](https://github.com/your-handle/transformerlens-classifier) — 864 attention features across 144 heads, four cognitive task types, Layer 0 dominance finding

## Systems

**Decentralised ML experiment coordination**
Built a complete Kademlia DHT in Go as the foundation for a decentralised experiment result store — motivated by the limitations of centralised tools (W&B, MLflow) for distributed research teams. Validated across 1,000+ node Docker simulations with fault injection, message dropout, and routing table healing.

- [Kademlia DHT](https://github.com/your-handle/kademlia-repo) — production-grade distributed hash table in Go, large-scale fault injection simulation
- [Neuromorphic SNN Training Framework](https://github.com/your-handle/snn-framework) — experiment management for SNN/ANN training on RadioML 2018.01A, multiple architectures and training rules

## Background

25 years building production systems across supply chain, mining, and transportation — geospatial algorithms, distributed data pipelines, cloud infrastructure. Now applying that systems depth to ML research infrastructure and mechanistic interpretability.

MSc Applied Artificial Intelligence, Luleå University of Technology (expected May 2027)

Google Cloud Certified Professional Data Engineer

## Contact

[LinkedIn](https://linkedin.com/in/stefanhoglund1) · Stefan.Hoglund@gmail.com · Colorado, USA
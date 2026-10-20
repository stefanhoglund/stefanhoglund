# Stefan Höglund

**Empirical AI Safety · LLM Evaluations · Research Engineering**

I am a software and data engineer with 25 years of experience building production systems, data platforms, and distributed infrastructure. My recent work focuses on empirical research into language-model behavior, interpretability, and evaluation methods for reliable AI systems.

I am particularly interested in how language models and AI agents behave when explicit instructions, authorization policies, and contextual information conflict—and how we can evaluate and maintain meaningful human oversight of increasingly capable systems.

My work combines controlled behavioral experiments, model analysis, and practical research engineering.

## Research Interests

- **AI safety evaluations:** Behavioral robustness, instruction conflicts, authorization boundaries, and safe tool use.
- **Agent oversight:** Permission-aware decisions, trusted versus untrusted context, and reliable behavior in changing environments.
- **Mechanistic interpretability:** Internal representations, attention patterns, and task-related information in language models.
- **Research engineering:** Reproducible experiments, evaluation infrastructure, and realistic environments for testing AI systems.

## Selected Research

### Authorization Behavior Under Competing Context
**BlueDot Impact Technical AI Safety Project Sprint · 2026**

A cross-model behavioral benchmark investigating how language models make authorization decisions when explicit policy conflicts with competing contextual information.

Evaluated **7 instruction models across 100 scenarios and 11 conditions (7,700 evaluations)**.

Key findings:
- Clean authorization accuracy ranged from 92% to 99%, but robustness under conflicting context varied substantially.
- Contradictory claims about user authorization state produced the highest decision-flip rates in six of seven models.
- Models exhibited distinct susceptibility profiles and, in most cases, directional asymmetry in authorization decisions.
- Separating semantic decision accuracy from strict output-format compliance proved important for cross-model evaluation.

The project motivates further research into contextual authority, information provenance, and safe agent authorization.

[**Research repository and report →**](https://github.com/stefanhoglund/authorization-behavior)

### Governed Natural Language-to-SQL Generation
**MSc Computer Science and Engineering Thesis · 2026**

Empirical and mechanistic investigations of language-model behavior in structured-data tasks.

- Studied task-related information in model activations using 192 lexically controlled prompts.
- Developed activation-based classifiers and analyzed attention features across transformer architectures.
- Constructed a governed NL-to-SQL benchmark with 52 questions and six ablation conditions, evaluated across multiple instruction models.

The research explores how language models represent task information and respond to structured constraints.

[**MSc Thesis (DiVA)**](https://urn.kb.se/resolve?urn=urn:nbn:se:ltu:diva-117810) 
[**Experiments →**](https://github.com/stefanhoglund/llm-sql-mechanistic-interpretability)

### Attention-Based Task Classification

Used TransformerLens and supervised classifiers to investigate whether transformer attention features contain information about prompt task categories. Experiments with GPT-2-small identified informative early-layer attention features, motivating further investigation of representation, generalization, and causal interpretation.

[**Attention pattern study →**](https://github.com/stefanhoglund/attention-task-classification)

## Selected Research Engineering

### Distributed Experiment Infrastructure

Built a Kademlia-based distributed hash table in Go, including routing, replication, fault injection, network disruption, and simulation with more than 1,000 Docker-based nodes.

This work reflects my interest in building reliable infrastructure for distributed experimentation and large-scale evaluation.

[**Kademlia distributed systems project →**](https://github.com/stefanhoglund/kademlia-ml-experiment-store)

## Background

Before moving into AI research, I spent over two decades designing and implementing software, analytics systems, cloud data platforms, and distributed applications across transportation, mining, supply chain, and public-sector organizations.

I bring experience translating ambiguous real-world problems into working systems, combining hands-on engineering with system-level understanding of organizational workflows, permissions, and governance.

**Education**
- MSc Computer Science and Engineering — Luleå University of Technology, 2026
- MSc Applied Artificial Intelligence — Luleå University of Technology, in progress
- MSc Data Science — Luleå University of Technology, in progress

**Certification:** Google Cloud Professional Data Engineer

## Connect

[GitHub](https://github.com/stefanhoglund) · [Google Scholar](https://scholar.google.com/citations?user=p2FBNDsAAAAJ) · [LinkedIn](https://linkedin.com/in/stefanhoglund1) · [Personal Website](https://stefanhoglund.com)

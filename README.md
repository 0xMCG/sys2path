# Sys2Path

🔵 [Sys2Path paper]()

🔵 [Get started with Sys2Path]()

## 🌟 Background and Motivation

Inspired by cognitive science, physics, and a reflection on the evolving nature of AI, we examine the dual-process theory of cognition—System 1 and System 2 thinking—as a foundation for advancing AI reasoning capabilities. First introduced by psychologist Daniel Kahneman, this framework differentiates between:

- **System 1 (Intuition)**: Fast, automatic, and often subconscious thinking.
- **System 2 (Reasoning)**: Slow, deliberate, and logical thinking.

### Connecting System 1 and 2 Thinking to AI

In his recent [*NeurIPS talk*](https://www.youtube.com/watch?v=WQQdd6qGxNs&t), Ilya Sutskever proposed a compelling analogy: envisioning Large Language Models (LLMs) as an "intuition layer" analogous to System 1, while emphasizing the need to develop reasoning and understanding capabilities akin to System 2. According to Sutskever, bridging this gap is essential for achieving superintelligence. Key insights include:

- **Intuition Layer as a Foundation**: LLMs excel in generating contextually relevant responses but lack robust reasoning.
- **The Reasoning Challenge**: Building AI systems that can reason unpredictably and creatively, much like expert chess moves or solving complex problems, remains a critical milestone.
- **Understanding Beyond Data**: Advanced AI must generalize and synthesize information efficiently, even with sparse data.

This dual-layer vision resonates with our pursuit of enabling AI to blend intuitive knowledge retrieval with structured, adaptive reasoning to address complex, real-world challenges. By modeling the interplay of intuition and reasoning, we aim to construct a framework that reflects both System 1 and System 2 processes in AI.

### Connecting System 2 Thinking to Test-Time Compute

Noam Brown, in [*his talk*](https://www.youtube.com/watch?v=eaAonE58sLU) on AI breakthroughs in games like poker, Go, and Diplomacy, highlighted the pivotal role of search/planning algorithms in achieving frontier capabilities. These algorithms, as test-time compute, align with System 2 thinking, enabling deliberate and adaptive reasoning. In contrast, pre-training of LLMs—train-time compute—aligns with System 1 thinking, providing a foundation of intuitive knowledge.

Hugging Face’s recent blog post, [*Scaling Test-Time Compute with Open Models*](https://huggingface.co/spaces/HuggingFaceH4/blogpost-scaling-test-time-compute), further emphasizes the importance of test-time compute in enhancing AI capabilities. By focusing on System 2 thinking as a next frontier, the AI community seeks to address challenges such as:

- **Resource Efficiency**: Leveraging test-time compute without excessive overhead.
- **Dynamic Reasoning**: Adapting pre-trained models for real-time, task-specific insights.

Our project, **Sys2Path**, aims to fill this gap by introducing a novel framework to enrich the possibilities of test-time compute, paving the way for AI systems that can reason dynamically and effectively.

---

## 📚 Inspirations from Cognitive Science Literature

### System 1 and System 2 Thinking

The concept of System 1 and System 2 thinking, introduced by Daniel Kahneman in [*Thinking, Fast and Slow*](https://en.wikipedia.org/wiki/Thinking,_Fast_and_Slow), serves as the foundation for understanding human cognition. System 1 processes are fast and intuitive, while System 2 is slower and deliberate, often stepping in to solve problems that require logic and reflection.

### Network Structure of Memory

Semantic memory, as described in [*A Critical Review of Network-Based and Distributional Approaches to Semantic Memory Structure and Processes*](https://pubmed.ncbi.nlm.nih.gov/34092042/), is structured as a network, where concepts are represented as nodes and relationships as edges. This structure enables:

- **Interconnectivity**: High-knowledge individuals demonstrate tightly connected networks.
- **Efficiency**: Shorter paths between nodes facilitate rapid learning and retrieval.

This network-inspired design is mirrored in structured semantic memory models for AI.

### Ranking and Prioritization in Memory

Research shows that not all memory nodes hold equal importance, as detailed in [*Mapping the Memory Structure of High-Knowledge Students: A Longitudinal Semantic Network Analysis*](https://www.mdpi.com/2079-3200/12/6/56). Salient nodes are prioritized based on:

- **Relevance**: Central nodes play a crucial role in memory retrieval.
- **Frequency and Emotional Weight**: These factors enhance recall and decision-making.

This principle of prioritization is a core feature of multi-ranked contextual graphs in AI frameworks.

### Dynamic Adaptation of Memory

Memory networks evolve dynamically, becoming more clustered and optimized with experience. Central concepts emerge through natural processes of reinforcement and optimization, as evidenced by *Dynamic Adaptation in Memory Networks: A Computational Perspective*. Similarly, adaptive memory evolution aligns closely with frameworks designed for AI learning and inference.

---

## 🔍 Introduction of Sys2Path

### High-Level Project Overview

The name **Sys2Path** encapsulates our mission: to build "System 2" reasoning capabilities within AI systems, inspired by the dual-process theory of cognition, and to create structured knowledge paths for reasoning and insight generation.

Inspired by cognitive science and physics, we introduce a holistic cognitive framework for AI reasoning, built atop Large Language Models (LLMs). This framework combines structured semantic memory with advanced reasoning capabilities to enable dynamic synthesis and insight generation.

### Key Components:

1. **Multi-Ranked Contextual Graphs**:
   - A structured semantic memory system that prioritizes and organizes information efficiently. It mirrors how the brain filters and stores knowledge, providing the foundation for dynamic and task-specific retrieval.

2. **Path Integral for Advanced Reasoning**:
   - Serving as the cognitive engine, the Path Integral synthesizes and integrates relationships across the memory graph. It identifies the Shortest Path for efficient connections and constructs the Minimal Viable Graph (MVG) for solving complex tasks. This mirrors higher-order cognitive processes like reflection, insight generation, and adaptive problem-solving.

Together, these components form a holistic approach that enables AI systems to dynamically organize, synthesize, and reason about knowledge, driving continuous learning and adaptability.

### System 2.1 and System 2.2

Sys2Path integrates:

- **System 2.1: Multi-Ranked Contextual Graphs (CG)**:
  - A network layer prioritizing nodes by relevance and importance, akin to a structured semantic memory that underpins rapid retrieval.

- **System 2.2: Knowledge Path Integral (KPI)**:
  - A reasoning layer that synthesizes insights by calculating the shortest paths and constructing the Minimal Viable Graph (MVG), mirroring search/planning algorithms in games to achieve deliberate reasoning and insight generation.

These algorithms empower Sys2Path to tackle complex tasks by blending intuitive memory structures with advanced reasoning capabilities, bridging the gap between System 1 and System 2 thinking in AI.

# Core Idea
The CMKG-Reasoner framework aims to enable reliable reasoning in artificial intelligence systems
by combining multimodal perception with causal knowledge graph reasoning. Instead of relying only
on correlations between modalities such as images, audio, and text, the system extracts events and
entities from multimodal data and represents their cause–effect relationships in a Multimodal
Causal Knowledge Graph (CMKG). This graph structure supports interpretable reasoning and
reduces hallucinations in AI systems.

# Main Features
1. Multimodal event and entity extraction from image, audio, video, and text inputs.
2. Construction of a Multimodal Causal Knowledge Graph representing causal relations between
events.
3. Graph-based representation learning to encode nodes, relations, and causal paths.
4. Causal reasoning engine capable of multi-hop reasoning over causal chains.
5. Integration with Large Language Models for explanation generation and reasoning transparency.

# Basic Architecture
1. Multimodal Input Layer: Collects images, audio, video, and text.
2. Feature Extraction: Uses modality-specific encoders to extract entities and events.
3. Causal Relation Extraction: Identifies cause–effect relationships between events.
4. Multimodal Causal Knowledge Graph: Stores entities, events, and causal relations.
5. Graph Representation Learning: Learns embeddings for nodes and relations.
6. Causal Reasoning Engine: Performs inference over causal paths.
7. LLM Explanation Layer: Generates interpretable reasoning explanations.

# Component: Purpose
1. Multimodal Encoders: Extract entities and events from different modalities
2. Causal Relation Extractor: Identify causal links between events
3. CMKG Builder: Construct causal knowledge graph
4. Graph Neural Network: Learn graph representations
5. Reasoning Engine: Perform causal inference
6. LLM Layer: Provide explanations and reasoning output

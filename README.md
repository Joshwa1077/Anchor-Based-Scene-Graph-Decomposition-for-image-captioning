Overview
This project enhances image captioning by introducing Anchor-Based Scene Graph Decomposition (ASGD). The system focuses on accurately describing complex visual scenes by constructing structured scene graphs and leveraging attention-based LSTM networks for caption generation.

Key components include:

Scene Graph Generation for object and relationship detection.
Subgraph Proposal Network (sGPN) to identify meaningful components.
Attention-based LSTM Networks for accurate and diverse caption generation.

Features
Anchor-Based Scene Graphs: Efficient decomposition of visual content into meaningful subgraphs.
Attention Mechanisms: Improved contextual understanding for generating descriptive captions.
Metrics Evaluation: Comprehensive evaluation using BLEU, CIDEr, and ROUGE-L scores.

Applications:
Assistive technologies for visually impaired individuals.
Enhanced perception in autonomous vehicles.
Automated content generation for e-commerce.
Real-time surveillance for security systems.

Architecture
The project comprises the following modules:

Scene Graph Generation
Detects objects, attributes, and relationships using pre-trained models.
Subgraph Proposal Network (sGPN)
Samples meaningful subgraphs for refined representation.
Caption Generation Module
Utilizes attention-based Long Short-Term Memory (LSTM) networks.

Evaluation Metrics
BLEU-1, BLEU-2, BLEU-3, BLEU-4, CIDEr, and ROUGE-L scores.


Anchor-Based Scene Graph Decomposition for Image Captioning
Overview
This project enhances image captioning by introducing Anchor-Based Scene Graph Decomposition (ASGD). The system focuses on accurately describing complex visual scenes by constructing structured scene graphs and leveraging attention-based LSTM networks for caption generation.

Key components include:

Scene Graph Generation for object and relationship detection.
Subgraph Proposal Network (sGPN) to identify meaningful components.
Attention-based LSTM Networks for accurate and diverse caption generation.

Features
Anchor-Based Scene Graphs: Efficient decomposition of visual content into meaningful subgraphs.
Attention Mechanisms: Improved contextual understanding for generating descriptive captions.
Metrics Evaluation: Comprehensive evaluation using BLEU, CIDEr, and ROUGE-L scores.

Applications:
Assistive technologies for visually impaired individuals.
Enhanced perception in autonomous vehicles.
Automated content generation for e-commerce.
Real-time surveillance for security systems.

Architecture
The project comprises the following modules:

Scene Graph Generation
Detects objects, attributes, and relationships using pre-trained models.
Subgraph Proposal Network (sGPN)
Samples meaningful subgraphs for refined representation.
Caption Generation Module
Utilizes attention-based Long Short-Term Memory (LSTM) networks.

Evaluation Metrics
BLEU-1, BLEU-2, BLEU-3, BLEU-4, CIDEr, and ROUGE-L scores.
Results
The system demonstrates superior performance in contextual understanding and caption diversity:

BLEU-1: 0.772
BLEU-2: 0.609
BLEU-3: 0.462
BLEU-4: 0.346
CIDEr: 1.144
ROUGE-L: 0.561

Technologies Used
Python
PyTorch
Graph Neural Networks (GNNs)
Attention-based LSTM
Image Captioning Models

Applications
Assistive Technologies: Enhancing accessibility for visually impaired users.
Autonomous Vehicles: Improved scene understanding for better navigation.
E-Commerce Platforms: Automating product descriptions using image captions.
Surveillance Systems: Real-time monitoring with accurate scene description.

Challenges and Future Work
Challenges:
Computational demands for graph-based processing.
Dependency on annotated datasets for training.

Future Work:
Optimization using Transformer architectures for better efficiency.
Domain-specific training for enhanced generalization.

Contributors
Joshwa Joy Philip - Model Development & Implementation

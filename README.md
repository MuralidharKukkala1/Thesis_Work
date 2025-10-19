Disease Symptom Profiling using Symptom–Treatment Knowledge Graphs

📄 Overview

This research focuses on constructing an ontology-enriched, interpretable, and scalable knowledge graph for profiling contagious and chronic diseases. The aim is to integrate natural language processing (NLP) and Graph Neural Networks (GNNs) to enhance medical data understanding, prediction, and interpretability.

By extracting biomedical entities such as symptoms, treatments, and diseases using Named Entity Recognition (NER) (via SpaCy and BioBERT models) and linking them through graph-based relationships, the project builds a disease-symptom-treatment knowledge graph. This enables more effective disease profiling, supporting clinical decision-making and risk prediction.

⚙️ Technical Approach

Biomedical NER Processing:

Uses SpaCy and BioBERT for entity extraction from medical text.

Identifies and categorizes terms into symptoms, treatments, and diseases.

Knowledge Graph Construction:

Entities are linked using semantic relationships to form a structured knowledge graph.

Incorporates ontology principles to ensure consistency and interoperability.

Graph Neural Networks (GNNs):

GNNs learn from graph structure to predict disease connections and treatment patterns.

Incorporates GNNExplainer for interpretability and SHAP for feature importance analysis.

Disease Profiling:

The final graph aids in understanding disease chronicity and contagiousness.

Supports personalized treatment insights and predictive analytics in healthcare.

🧩 Research Foundation

This work is aligned with the ideas proposed by:

Boll et al. (2024): Application of GNNs for clinical risk prediction using Electronic Health Records (EHRs), emphasizing privacy assurance and multimodal health data integration.

Khemani et al. (2024): Technical evolution of GNN architectures, addressing challenges in heterogeneous graphs, dynamic modeling, and responsible AI in healthcare.

Together, these papers form the base of this thesis, combining medical relevance with state-of-the-art GNN methodologies to create interpretable and practical health informatics tools.

🎯 Objectives

Build a comprehensive symptom–treatment knowledge graph.

Use GNNs to enhance prediction and explainability of disease relationships.

Address privacy, interpretability, and scalability challenges in healthcare AI.

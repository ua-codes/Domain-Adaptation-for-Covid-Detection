COVID-19 AGCA Hybrid Model

This repository contains the implementation of a Hybrid Neuro-Symbolic model designed for the automated classification of COVID-19 and CAP-Pneumonia from CT scan slices. The project focuses on improving model interpretability through Attention-Guided Feature Extraction and Symbolic Logic Fusion.

📁 Project Structure
The repository is organized as follows:

notebooks/: Contains the main .ipynb implementation (Training, Evaluation, and Explainability).

reports/: Final Research Report detailing methodology and ablation studies.

presentations/: Thesis defense slides and project overview.

data/: Documentation and links to the datasets used.

models/: Saved model checkpoints and weights.

🧠 Model Architecture: AGCA Hybrid
The core of this research is the AGCA (Attention-Guided Component Analysis) Hybrid model. It consists of three primary modules:

Attention-Guided Backbone: A ResNet-50 modified with custom Attention Gates to localize infection hotspots.

Symbolic Logic Mapper: A secondary head that predicts clinical indicators (e.g., Ground Glass Opacity, Consolidation).

Uncertainty-Aware Fusion: A reasoning engine that uses Shannon Entropy to balance CNN predictions with symbolic logic rules.

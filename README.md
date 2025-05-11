# NeuroSketch_Results
The detailed results of NeuroSketch, including the roadmap and experiment part.
# Roadmap Part
This directory contains results from various model experiments and the research roadmap, covering three main areas:
- **Basic Architecture Study**: Fundamental model architecture exploration  
- **Macro Study**: Large-scale structure analysis such as module composition, network depth, and parallel structures  
- **Micro Study**: Fine-grained component analysis such as activation functions, kernel sizes, and normalization techniques  
---
## 📊 Experiment Format
All experimental results are logged in table format, where each row represents a single experiment. The table includes the following columns:
| Field               | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Name**            | Name of the experiment, formatted as `Model+Task+SubjectID`, e.g., `ResNet50-Classification-S01` |
| **Accuracy (val/test)** | Accuracy on validation and test sets                                      |
| **Precision (val/test)** | Precision on validation and test sets                                      |
| **F1 (val/test)**   | F1 score on validation and test sets                                         |
| **FLOPs**           | Computational complexity (floating-point operations)                        |
| **Params**          | Number of model parameters                                                   |
---
## 🧠 Directory Structure
Results_Roadmap/
├── basic_architecture/
│   ├── resnet_cls_S01/
│   │   ├── code/
│   │   └── results.csv
├── macro_study/
│   └── ...
├── micro_study/
│   └── ...
└── README.md


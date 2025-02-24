# SST-ResNet: A sequence and structure information integration model for protein property prediction
## Method
Predicting protein properties based on amino acid sequences and 3D structures has become a key approach to accelerating drug development.   In this study, we propose a novel sequence- and structure-based framework, SST-ResNet, which consists of the multimodal language model ProSST and a multi-scale information integration module.   This framework is designed to deeply explore the latent relationships between protein sequences and structures, thereby achieving superior synergistic prediction performance.   Our method outperforms previous joint prediction models on Enzyme Commission (EC) numbers and Gene Ontology (GO) tasks.   Furthermore, we demonstrate the necessity of multi-scale information integration for these two types of data and illustrate its exceptional performance on key tasks.   We anticipate that this framework can be extended to a broader range of protein property prediction problems, ultimately facilitating drug development.
![2e9caa192095a10d181ef678718f0331_720](https://github.com/user-attachments/assets/46c1ce73-e213-44b7-bbfb-ba5596b4d3c7)


## Model
We used the open-source ProSST model on HuggingFace, utilizing a structure vocabulary of size 2048. https://huggingface.co/AI4Protein/ProSST-2048

## Data
The sample data and label data for EC and GO were downloaded via the link provided by TorchDrug and were converted according to the processing script.https://github.com/DeepGraphLearning/torchdrug/tree/master/torchdrug/datasets

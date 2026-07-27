# K-DAF

K-DAF is a project for training and evaluating multi-turn psychotherapy dialogues. It includes datasets, client profiles, LoRA fine-tuning configurations, and automated evaluation scripts.

## Project Structure

```text
K-DAF/
├── dataset/                    # PsyDAF training/validation sets and psychotherapy knowledge base
├── extract_client_profiles/    # Client profile generation script and generated results
├── evaluation/                 # Automated dialogue scoring script (WAI, BLRI, and CCS-R)
├── env/                        # Dependency lists for training and dataset construction
├── llamafactory/               # LLaMA-Factory source code and training, merging, and inference configs
└── models/                     # Local model directory
```

`llamafactory/train_model/` contains LoRA fine-tuning configurations, while `merge_lora/` and `inference/` provide configurations for model merging and inference, respectively.

> Model, dataset, and output paths in the configuration files are placeholders and must be adapted to the local environment before use. This project is intended for research and experimentation only; it is not a substitute for professional psychological counseling or clinical diagnosis.

## Acknowledgments

The model training, merging, and inference workflow in this project is built on [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory). We thank its contributors for their open-source work. Please comply with its license and copyright notices when using the related code.

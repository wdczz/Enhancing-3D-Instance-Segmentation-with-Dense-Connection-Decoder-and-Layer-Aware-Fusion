# Enhancing 3D Instance Segmentation with Dense Connection Decoder and Layer Aware Fusion (RAL2025)

Duanchu Wang, Gonghao Ran, and Di Wang

![Overview](docs/overview.png)

This is the official implementation of paper "Enhancing 3D Instance Segmentation with Dense Connection Decoder and Layer-Aware Fusion".



## 📰 News
- **2025-08-04**: 🎉 Our paper has been accepted by RAL 2025!

## ⚙️ Training Hyperparameters

Key training hyperparameters for all datasets:

| Dataset | Optimizer | LR | Schedule | Weight Decay | BS | Epochs | Warmup |
|---------|-----------|---|--------|--------------|----|--------|--------|
| ScanNetV2 | AdamW | 0.001 | PolyLR | 0.05 | 4 | 512 | 10 |
| ScanNet200 | AdamW | 0.001| PolyLR | 0.05 | 4 | 512 | 10 |

## 📝 TODO
- [ ] 🚀 Release trained weights and experiment record
- [ ] 📦 Installation instructions
- [ ] 🗃️ Processing datasets
- [ ] ⚙️ Release training configs
- [ ] 💻 Release training code

# Second Challenge of the PoliMi course of Artificial Neural Networks and Deep Learning, 2025

## Histological Image Classification & Omni-Ensemble

In this challenge, we tackled an image classification task to categorize histopathological breast cancer tissue samples into four clinical subtypes (**HER2(+), Luminal A, Luminal B, and Triple Negative**). Facing real-world challenges like background noise, visual artifacts, and limited data, we adopted a data-centric preprocessing approach utilizing smart cropping and high-resolution training alongside heavy data augmentation. By building an Omni-Ensemble that aggregates predictions across 23 diverse models from the EfficientNet, ResNet, ResNeXt, and DenseNet families—combined with 8-view test-time augmentation—our approach successfully maximized generalization.

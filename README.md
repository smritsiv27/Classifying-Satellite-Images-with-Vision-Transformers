# Classifying-Satellite-Images-with-Vision-Transformers
Fine-tuning on DeiT and DINOv2 for analyzing building damage after natural disasters.

Rapid building damage assessment is critical for post-disaster response. Damage classification
models built on satellite imagery provide a scalable means of obtaining situational awareness.
However, label noise and severe class imbalance in satellite data create major challenges. The
xBD dataset offers a standardized benchmark for building-level damage across diverse geographic
regions. 
In this study, we evaluate Vision Transformer (ViT) model performance on the xBD dataset, specifically investigating how these models distinguish between types of structural damage when training on noisy, imbalanced data.

In this study, we specifically evaluate DINOv2-small and DeiT for multi-class damage classi-
fication. We propose a targeted patch-based pre-processing pipeline to isolate structural features and minimize background noise in training. We adopt a frozen-head fine-tuning strategy to keep computational requirements manageable.

Model performance is evaluated through accuracy, precision, recall, and macro-averaged F1
scores. We show that small ViT architectures with our novel training method achieves competitive macro-averaged F1 relative to prior CNN baselines for disaster classification.

# Cognitive-decline-D-CVAE
This repository contains the implementation of the Disentangled Conditional Variational Autoencoder (D-CVAE) for clinically interpretable prediction of cognitive impairment stages (CN, MCI, AD). The model fuses neuropsychological scores and demographic data while learning a disentangled latent representation that aligns with disease progression.
# Model Description
The D-CVAE Fusion framework combines:
1.Disentangled representation learning via conditional VAE
2.Stage-aligned supervision loss for interpretable latent factors
3.Multimodal fusion of cognitive, clinical, and demographic features
4.A lightweight MLP classifier head for stage prediction
It is evaluated on the OASIS-3 dataset and demonstrates strong generalization and interpretability, achieving 94.52% accuracy with statistically significant improvement over standard baselines.


# Expected Output Logs
[Epoch 10] Train Loss: 0.0321 | Val Accuracy: 93.12%
[Epoch 20] Train Loss: 0.0273 | Val Accuracy: 94.11%
...
Test Accuracy: 94.52%
Latent z₁ ↔ MMSE Correlation: r = -0.94
# requirements.txt
torch
numpy
pandas
scikit-learn
matplotlib

# Contact
For questions, contact: [nbp.cse@rmkec.ac.in,snk.cse@rmkec.ac.in]



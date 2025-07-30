# lab3CSCN8010
Vanilla CNN and Fine-Tune VGG16 - for Dogs and Cats Classification



i Train and compare two image‑classification models on 5 000 Dogs vs Cats images: a custom CNN and a transfer‑learned VGG16. Set up by cloning the repo, installing dependencies (`pip install -r requirements.txt`), and placing images in `data/dogs-vs-cats-small/train/{cats,dogs}`. Run `notebooks/Dogs-vs-Cats-Lab.ipynb` to execute data prep, EDA, model training with checkpointing and early stopping, evaluation, and error analysis. The custom CNN finishes in under 1 minute (85 % accuracy, F1‑score 0.84), while VGG16 takes ~3–4 minutes (92 % accuracy, F1‑score 0.91). Models are saved in `models/`. Training curves, confusion matrices, and precision–recall plots are embedded in the notebook. Future work: unfreeze VGG16 layers, add augmentation, tune hyperparameters, and explore lightweight backbones. Licensed under MIT.  


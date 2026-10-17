# Dataset

The dataset is **not included** in this repository (size / licensing).
Place your copy here (or upload it to Google Drive for Colab) with this layout:

```
dataset/
├── gun/         knife/        shuriken/        safe/     # X-ray images
└── annotations/
    ├── gun/     knife/        shuriken/                  # segmentation masks
```

- Each mask must share its image's base filename (`.png`, `.jpg`, or `.jpeg`).
- Mask object pixels are non-zero (e.g. 255); the code binarizes them with `mask > 0`.
- `safe/` images have no threat and are not used by the current binary U-Net training.
- Dataset source: **[ADD LINK / CITATION]**

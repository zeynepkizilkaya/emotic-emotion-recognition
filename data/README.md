# EMOTIC Dataset

## Download Instructions

The EMOTIC dataset is not included in this repository due to its large size.

### Steps to Download:

1. Visit the official EMOTIC project page
2. Request dataset access from the authors
3. Download the dataset files
4. Extract to this directory

### Expected Directory Structure:
```
data/
├── emotic/
│   ├── ade20k/           (432 images)
│   ├── emodb_small/      (1,374 images)
│   ├── framesdb/         (4,884 images)
│   └── mscoco/           (16,544 images)
│
└── Annotations/
    └── Annotations.mat   (Emotion labels and bounding boxes)
```

### Dataset Statistics:

- **Total Images:** 23,234
- **Training Samples:** 17,077
- **Validation Samples:** 2,088
- **Test Samples:** 4,398
- **Emotion Categories:** 26 (multi-label)

### Citation:
```
@article{kosti2017emotic,
  title={Context based emotion recognition using emotic dataset},
  author={Kosti, Ronak and Alvarez, Jose M and Recasens, Adria and Lapedriza, Agata},
  journal={IEEE TPAMI},
  year={2017}
}
```

**Note:** Dataset files are NOT tracked by git (see `.gitignore`).

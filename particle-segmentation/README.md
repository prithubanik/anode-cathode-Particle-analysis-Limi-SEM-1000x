# Microscopy Particle Segmentation

Computer-vision experiments for particle segmentation and analysis in microscopy images.

## Model-based structure

```text
particle-segmentation/
├── yolo/
├── sam/
├── mask-rcnn/
├── unet/
└── README.md
```

Each model family is kept separate so experiments can be compared and maintained independently.

- **YOLO** — YOLO-based detection/segmentation experiments
- **SAM** — Segment Anything / SAM3-based segmentation experiments
- **Mask R-CNN** — instance segmentation and particle feature extraction
- **U-Net** — U-Net segmentation experiments

Only notebooks that are actually related to particle segmentation are included in this repository.

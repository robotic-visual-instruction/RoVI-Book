# RoVI-Book Dataset

## Introduction
RoVI-Book is a dataset focused on robotic manipulation and visual understanding for robotic visual instruction. The dataset contains a large collection of sequential images capturing robot operations, covering both single-step and multi-step manipulation scenarios.

## Dataset Structure

```
dataset/
├── dataset_llava.json          # Dataset file in LLaVA format
└── obs/                        # Observation data
    ├── pics_multi_step/        # Multi-step operation images
    │   ├── circle/            # Images with circle annotations
    │   └── no_circle/         # Images without annotations
    ├── pics_one_step/         # Single-step operation images
    │   ├── circle/           # Images with circle annotations
    │   └── no_circle/        # Images without annotations
    └── rotation/              # Rotation-related images
        ├── multi_step/       # Multi-step rotation operations
        └── one_step/         # Single-step rotation operations

```

## Dataset Features
- Contains both single-step and multi-step operation sequences
- Provides annotated and unannotated versions of images
- Covers various robotic manipulation scenarios:
  - Object manipulation
  - Container handling
  - Tool usage
  - Object flipping
  - Drawer operations and more

## Image Categories
1. Multi-step Operation Images: Recording complete operation sequences
2. Single-step Operation Images: Capturing individual actions
3. Rotation Operation Images: Focusing on object flipping and rotation actions

## Annotation Information
- circle/: Contains images with circle annotations 
- no_circle/: Contains images without circle annotations 
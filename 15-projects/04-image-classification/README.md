# Image Classification with CNN

**Goal**: Classify CIFAR-10 images into 10 categories using a CNN.

## Architecture
- 2 Conv blocks with BatchNorm + MaxPool
- Dropout for regularization
- Adam optimizer with StepLR scheduler

## Expected Results
- ~65-70% accuracy after 10 epochs on CIFAR-10
- Use GPU for faster training

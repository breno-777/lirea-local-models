# Lirea Layout Seg v5 (mobile 720)

ONNX FP16 layout detector for comic/manga pages, calibrated at 720x720 for mobile CPU/XNNPACK.

- Input: `input` [1, 3, 720, 720], ImageNet-normalized RGB
- Outputs: `dets` [1, 100, 4] normalized cxcywh, `labels` [1, 100, 5] logits, `masks` [1, 100, 180, 180]
- Classes: 0 bubble, 1 text_bubble, 2 text_free, 3 sfx
- File: `lirea-layout-seg-v5-mobile.onnx`
- Size: 73,030,389 bytes
- SHA-256: `1f37c95847e8c7acd02663decbc29c384f43e932b47228ee9cfc830b392d4526`

Trained by the Lirea Vision layout-model pipeline (RF-DETR-Seg Small).

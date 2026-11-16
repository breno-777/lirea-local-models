# Lirea Layout Seg v5 (mobile 720)

ONNX INT8 dynamic layout detector for comic/manga pages, calibrated at 720x720 for mobile CPU/XNNPACK.

- Input: `input` [1, 3, 720, 720], ImageNet-normalized RGB
- Outputs: `dets` [1, 100, 4] normalized cxcywh, `labels` [1, 100, 5] logits, `masks` [1, 100, 180, 180]
- Classes: 0 bubble, 1 text_bubble, 2 text_free, 3 sfx
- File: `lirea-layout-seg-v5-mobile-int8.onnx`
- Size: 44,778,062 bytes
- SHA-256: `3a664a7b6dbcb3ae844a2fd639442d849a458878aeefb53c60a40d87191356b1`

The FP16 export remains in this directory for desktop/reference use. The INT8
dynamic variant is the Android runtime artifact.


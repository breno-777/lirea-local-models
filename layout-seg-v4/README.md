# Lirea Layout Seg v4

ONNX INT8 (dynamic) layout detector for comic/manga pages.

- Input: `input` [1, 3, 864, 864], ImageNet-normalized RGB
- Outputs: `dets` [1, 100, 4] normalized cxcywh, `labels` [1, 100, 5] logits, `masks` [1, 100, 216, 216]
- Classes: 0 bubble, 1 text_bubble, 2 text_free, 3 sfx
- File: `lirea-layout-seg-v4-int8.onnx`
- Size: 47,574,692 bytes
- SHA-256: `6ccabc7165af2df1e41d41011833177cbc2392ae2cbdc08a5186ce0be3d7d6ae`

Trained by the Lirea Vision layout-model pipeline (RF-DETR-Seg Small, 864x864).

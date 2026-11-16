# Lirea local models

Model files downloaded on demand by the Lirea Android app. The APK does not
bundle these weights.

| Directory | Model | License |
|---|---|---|
| `layout-seg-v5/` | Lirea Layout v5 mobile detector (FP16 ONNX, 720) | Apache-2.0 |
| `layout-seg-v4/` | Lirea Layout v4 detector (INT8 ONNX, 864, legacy) | Apache-2.0 |
| `rtdetr/` | RT-DETR comic detector (legacy) | Apache-2.0 |
| `paddle-v5/` | PP-OCRv5 mobile det + rec + dict | Apache-2.0 |
| `paddle-v4/` | PP-OCRv4 mobile det + rec + dict (legacy) | Apache-2.0 |
| `yolo/` | YOLO MangaLens (legacy, license unverified) | **do not redistribute commercially** |

See `NOTICE` for upstream links, copyright notices and provenance. The app
downloads the files from this repository's `main` branch via raw GitHub URLs.

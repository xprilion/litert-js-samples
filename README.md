# litert-js-samples

Sample applications using [LiteRT.js](https://ai.google.dev/edge/litert/web), Google's browser runtime for TFLite models.

## Samples

- **[object-detection](./object-detection/)** — EfficientDet Lite0 detects 90 object types with bounding boxes. COCO classes, 4.3 MB.
- **[pose-estimation](./pose-estimation/)** — MoveNet Lightning detects 17 body keypoints with skeleton overlay. 2.8 MB.
- **[image-segmentation](./image-segmentation/)** — Selfie Segmenter separates person from background. Blur, B&W, or mask effects. 244 KB.
- **[image-classification](./image-classification/)** — MobileNetV4 running in the browser via WebGPU/WASM. Classify images with ImageNet labels.
- **[llm-chat](./llm-chat/)** — Gemma 4 E2B · Qwen3 0.6B · Granite 350M · DeepSeek 1.5B running locally in the browser via LiteRT-LM.

## Run locally

Any HTTP server works:

```bash
python3 -m http.server 8081 --bind 0.0.0.0
```

Then open `http://localhost:8081`.

# litert-js-samples

Sample applications using [LiteRT.js](https://ai.google.dev/edge/litert/web), Google's browser runtime for TFLite models.

## Samples

- **[image-classification](./image-classification/)** — MobileNetV4 running in the browser via WebGPU/WASM. Classify images with ImageNet labels.

## Run locally

Any HTTP server works. For example:

```bash
cd image-classification
python3 -m http.server 8081 --bind 0.0.0.0
```

Then open `http://localhost:8081`.

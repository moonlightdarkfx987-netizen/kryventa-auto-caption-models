# KryVenta Auto Caption Models

Versioned on-device speech-recognition models used by KryVenta Auto Captions.

## Accuracy-first English v2.0.0

- Model: Whisper Large v3 Turbo Q5_0 in official whisper.cpp GGML format
- File: `ggml-large-v3-turbo-q5_0.bin`
- Size: 574,041,195 bytes (547 MiB)
- SHA-256: `394221709cd5ad1f40c46e6031ca61bce88931e6e088c188294c6d5a55ffa7e2`
- Direct download: https://github.com/moonlightdarkfx987-netizen/kryventa-auto-caption-models/releases/download/v2.0.0/ggml-large-v3-turbo-q5_0.bin

KryVenta forces English recognition, uses accuracy-first beam search, and reports native inference progress. The model is downloaded on demand; the app verifies its exact byte length and SHA-256 before loading it.

The older small.en v1 release remains available only for release history and is not selected by current app builds.

## Attribution

The model and runtime are from [whisper.cpp](https://github.com/ggml-org/whisper.cpp), based on [OpenAI Whisper](https://github.com/openai/whisper). Upstream license: MIT.
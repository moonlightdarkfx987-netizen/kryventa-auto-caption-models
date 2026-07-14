# KryVenta Auto Caption Models

Versioned on-device speech-recognition models used by KryVenta Auto Captions.

## High-accuracy English v1.0.0

- Model: Whisper `small.en` in whisper.cpp GGML format
- File: `ggml-small.en.bin`
- Size: 487,614,201 bytes (465 MiB)
- SHA-256: `c6138d6d58ecc8322097e0f987c32f1be8bb0a18532a3f88f734d1bbf9c41e5d`
- Direct download: https://github.com/moonlightdarkfx987-netizen/kryventa-auto-caption-models/releases/download/v1.0.0/ggml-small.en.bin

The model is downloaded on demand and is not bundled in the KryVenta APK. The app must verify the byte length and SHA-256 before loading it.

## Attribution

The model format and runtime are provided by [whisper.cpp](https://github.com/ggml-org/whisper.cpp), based on [OpenAI Whisper](https://github.com/openai/whisper). Refer to the upstream projects for their licenses and model documentation.
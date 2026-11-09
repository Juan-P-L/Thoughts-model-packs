# Thoughts model packs

Public, immutable model-pack assets for the [Thoughts](https://github.com/Juan-P-L/Thoughts) Android app. This repository contains only the redistributed model weights and their license files; it contains no application source code.

The app downloads these assets once during model setup and verifies each byte count and SHA-256 before installing them.

## Release `model-packs-v1`

| Asset | Size (bytes) | SHA-256 |
| --- | --- | --- |
| `gemma3-1b-it-int4.litertlm` | 584417280 | `1325ae366d31950f137c9c357b9fa89448b176d76998180c08ceaca78bba98be` |
| `embeddinggemma-300M_seq512_mixed-precision.tflite` | 179132472 | `ad09e81557203cb0e177abf9bf8727dfe138a7d394aa0f70f0b2ed16432e121a` |

Download URLs:

- https://github.com/Juan-P-L/Thoughts-model-packs/releases/download/model-packs-v1/gemma3-1b-it-int4.litertlm
- https://github.com/Juan-P-L/Thoughts-model-packs/releases/download/model-packs-v1/embeddinggemma-300M_seq512_mixed-precision.tflite

The release also carries `NOTICE.txt` and `GEMMA_TERMS.md`.

## Source

These are unmodified copies of the LiteRT Community releases:

- `litert-community/Gemma3-1B-IT` — `gemma3-1b-it-int4.litertlm`
- `litert-community/embeddinggemma-300m` — `embeddinggemma-300M_seq512_mixed-precision.tflite`

## License

Gemma is provided under and subject to the Gemma Terms of Use found at gemma.ai/resources/terms

The Gemma Terms of Use, including the use restrictions in Section 3.2, govern the use and distribution of these artifacts. A copy of the terms is provided in `GEMMA_TERMS.md` and the required notice in `NOTICE.txt`. Gemma and EmbeddingGemma are trademarks of Google LLC.

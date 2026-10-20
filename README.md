# Savanna voices

Pinned, unmodified copies of the open-source voice components that [Savanna](https://savanna-app.github.io) downloads on demand.
Savanna fetches from here first and falls back to the original sources, and it refuses any file whose SHA-256 doesn't match the value pinned in the app.

| Release | What | Original source | License |
|---|---|---|---|
| `kokoro-f8ff771e` | Kokoro-82M CoreML: the built-in Natural voices | [aufklarer/Kokoro-82M-CoreML](https://huggingface.co/aufklarer/Kokoro-82M-CoreML) @ `f8ff771e` (model by [hexgrad](https://huggingface.co/hexgrad/Kokoro-82M)) | Apache-2.0 |
| `voicebox-0.5.0` | Voicebox 0.5.0, the local server behind voice cloning (signed and notarized by its authors) | [jamiepine/voicebox](https://github.com/jamiepine/voicebox/releases/tag/v0.5.0) · source: [Savanna-App/voicebox](https://github.com/Savanna-App/voicebox) | MIT |
| `qwen3-tts-0.6b-1eccf1cb` | Qwen3-TTS 0.6B Base (MLX bf16), the voice cloning model, split in two parts under 2 GiB | [mlx-community/Qwen3-TTS-12Hz-0.6B-Base-bf16](https://huggingface.co/mlx-community/Qwen3-TTS-12Hz-0.6B-Base-bf16) @ `1eccf1cb` (model by the [Qwen team](https://huggingface.co/Qwen/Qwen3-TTS-12Hz-0.6B-Base)) | Apache-2.0 |

Each release carries its license text and a `SHA256SUMS` file. The files are redistributed unchanged under their licenses; all rights to the models and software belong to their authors.

Releases are built with `scripts/mirror-voices.sh` in the Savanna source repository.

# eter-modelos

Copia del modelo que usa ETER (alpha), para no depender de que el original siga publicado.

- **Modelo:** `gemma-4-26B-A4B-it-ultra-uncensored-heretic-Q4_K_M` (cortado en 10 partes de menos de 2 GB con
  `llama-gguf-split`; llama.cpp lo carga apuntando a la parte `-00001-of-00010.gguf`) + `gemma-4-26B-A4B-it-mmproj-BF16.gguf`.
- **Origen:** [Arue-2026/gemma-4-26B-A4B-it-ultra-uncensored-heretic-GGUF](https://huggingface.co/Arue-2026/gemma-4-26B-A4B-it-ultra-uncensored-heretic-GGUF),
  cuantizado de [llmfan46/gemma-4-26B-A4B-it-ultra-uncensored-heretic](https://huggingface.co/llmfan46/gemma-4-26B-A4B-it-ultra-uncensored-heretic),
  basado en [google/gemma-4-26B-A4B-it](https://huggingface.co/google/gemma-4-26B-A4B-it).
- **Licencia:** Apache 2.0 (ver `LICENSE`), la misma del original. Gemma es una marca de Google.
- **Cambios:** ninguno en los pesos. Solo se cortó el archivo en partes: los 658 tensores son idénticos al original
  (sha256 del original sin cortar: `acae52237b2abba49223a346ff8154fa15489f103676e6d10107cfa099720e38`).
- **Huellas:** `SHA256SUMS`.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rodwell311/Notebook/blob/main/notebook_subtitle.ipynb)

# 🎬 Subtitle Extractor

Audio transcription & subtitle generator menggunakan:
- **Transcription**: [Qwen3-ASR-1.7B](https://huggingface.co/Qwen/Qwen3-ASR-1.7B) — 52 bahasa & dialek
- **Translation**: [NLLB-200-3.3B](https://huggingface.co/facebook/nllb-200-3.3B) — translate ke Bahasa Indonesia
- **Timestamps**: [Qwen3-ForcedAligner-0.6B](https://huggingface.co/Qwen/Qwen3-ForcedAligner-0.6B) — word-level timestamps

## Fitur
- ✅ Satu model ASR untuk semua bahasa (tidak perlu pilih engine)
- ✅ Tidak perlu login HuggingFace
- ✅ Output format: SRT, ASS, atau keduanya
- ✅ Auto-detect bahasa
- ✅ Translation otomatis ke Bahasa Indonesia

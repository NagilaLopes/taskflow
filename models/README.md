# Trained Models

ONNX INT8 quantized models (~240 MB total).

## Models

| Model | Size | Format | Status |
|-------|------|--------|--------|
| `classifier_int8.onnx` | 65 MB | ONNX INT8 | ⏳ Training |
| `extractor_int8.onnx` | 50 MB | ONNX INT8 | ⏳ Pending |
| `ner_int8.onnx` | 65 MB | ONNX INT8 | ⏳ Pending |
| `summarizer_int8.onnx` | 60 MB | ONNX INT8 | ⏳ Pending |

## Performance Targets

- Classification: F1 > 92% (target 94%)
- Extraction: F1 > 88% (target 92%)
- NER: F1 > 85% (target 89%)
- Summarization: ROUGE-L > 0.40 (target 0.42)

**Note:** Models excluded from git (use Git LFS or external storage).

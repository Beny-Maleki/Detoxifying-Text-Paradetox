# Detoxifying-Text-Paradetox

### `text_detoxification.ipynb`
This file consists of the code blocks that train a t5-small using instruction-finetuning for Hate Speech Modification. Instances of modification are taken from
[ParaDetox dataset](https://github.com/s-nlp/paradetox).

### `inference_preprocess_pipeline.ipynb`
This file registers a preprocessing stage to the inference pipeline of the input prompts, which automatically adds the _task definition_ before the prompt.

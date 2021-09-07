# Wav2vec2 Large XLSR 53 for Malayalam
This repository contains the code for [Wav2vec2 Large XLSR 53](https://huggingface.co/facebook/wav2vec2-large-xlsr-53) model fine-tuned on Malayalam (ml) language for Automatic Speech Recognition (ASR). We use multiple public datasets to fine-tune the model. This model was trained as part of XLSR fine-tuning week organized by [Hugging Face](https://huggingface.co/). The fine-tuned model can be directly used for downstream tasks from Hugging Face Models repository : https://huggingface.co/gvs/wav2vec2-large-xlsr-malayalam

## Datasets
- [IIIT-H Indic Speech Dataset](http://speech.iiit.ac.in/index.php/research-svl/69.html)  
- [Indic TTS Malayalam Speech Corpus](https://www.kaggle.com/kavyamanohar/indic-tts-malayalam-speech-corpus)  
- [SMC Malayalam Speech Corpus](https://blog.smc.org.in/malayalam-speech-corpus/)  
- [Openslr Malayalam Speech Corpus](http://openslr.org/63/)

The datasets needs to be converted to format suitable for Hugging Face Datasets library. This can be done using the notebook provided [here](make_hf_dataset.ipynb).

## Fine-tuning
The model can be fine-tuned using [this notebook](fine-tune-xlsr-wav2vec2-on-malayalam-asr-with-transformers).

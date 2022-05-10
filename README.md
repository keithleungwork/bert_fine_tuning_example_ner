# bert_fine_tuning_example_ner
An example of leveraging HuggingFace to fine-tune BERT model for NER task

The notebook is based on the [source here](https://github.com/ken11/bert-japanese-ner-finetuning/blob/master/bert-japanese-ner-finetuning-tohoku.ipynb). You will find most of the content are quite similar, except that I changed some processing and also translated into English.

The purpose of modification is that I wanted to try to use methods from TokenizerFast class, which is much more efficient and do the heavy work for us. Also wanted to do the IOB tagging manually instead of calling a 3rd party lib to do it, so we know more how data was tagged.
# NLP-projects


## Content
* [speech recognition with Tensorflow]() In this project a Convolutional Neural Network is implemented using TensorFlow in order to perform speech recognition. Additionally, inference will be run on the trained model using TensorFlow Lite to obtain a smaller model that is suitable for being deployed on a Raspberry Pi.
* [How to generate text: using different decoding methods for language generation with Transformers](https://github.com/avs-abhishek123/NLP-projects/blob/main/02_how_to_generate.ipynb) is a gives a brief overview of different decoding strategies and more importantly shows how you can implement them with very little effort using the popular transformers library!
* [Attention is All You Need](https://github.com/avs-abhishek123/NLP-projects/blob/main/6_Attention_is_All_You_Need.ipynb) is implementing a (slightly modified version) of the Transformer model from the [Attention is All You Need](https://jalammar.github.io/illustrated-transformer/) paper. 
* [Fine-tuning BERT for named-entity recognition](https://github.com/avs-abhishek123/NLP-projects/blob/main/Custom_Named_Entity_Recognition_with_BERT.ipynb) notebook, we are going to use BertForTokenClassification which is included in the Transformers library by HuggingFace. This model has BERT as its base architecture, with a token classification head on top, allowing it to make predictions at the token level, rather than the sequence level. Named entity recognition is typically treated as a token classification problem, so that's what we are going to use it for.
* [Tensor2Tensor](https://github.com/avs-abhishek123/NLP-projects/blob/main/Tensor2Tensor_Intro.ipynb), or T2T for short, is a library of deep learning models and datasets designed to make deep learning more accessible and accelerate ML research. T2T is actively used and maintained by researchers and engineers within the Google Brain team and a community of users. This colab shows you some datasets we have in T2T, how to download and use them, some models we have, how to download pre-trained models and use them, and how to create and train your own models.
* [Text generation with a miniature GPT](https://github.com/avs-abhishek123/NLP-projects/blob/main/text_generation_with_miniature_gpt.ipynb) implements an autoregressive language model using a miniature version of the GPT model. The model consists of a single Transformer block with causal masking in its attention layer. We use the text from the IMDB sentiment classification dataset for training and generate new movie reviews for a given prompt. When using this script with your own dataset, make sure it has at least 1 million words.
* [Fine_tune_CodeT5_for_generating_docstrings_from_Ruby_code](https://github.com/avs-abhishek123/NLP-projects/blob/main/Fine_tune_CodeT5_for_generating_docstrings_from_Ruby_code.ipynb)
* [PanGu-α](https://github.com/avs-abhishek123/NLP-projects/tree/master/PanGu-α) is a Large-scale autoregressive pretrained Chinese language model with up to 200B parameter. The models are developed under the [MindSpore](https://www.mindspore.cn/en) and trained on a cluster of [Ascend](https://e.huawei.com/en/products/servers/ascend) 910 AI processors.
* [NEZHA-TensorFlow](https://github.com/avs-abhishek123/NLP-projects/tree/master/NEZHA-TensorFlow) is a pretrained Chinese language model which achieves the state-of-the-art performances on several Chinese NLP tasks developed under TensorFlow.
* [NEZHA-PyTorch](https://github.com/avs-abhishek123/NLP-projects/tree/master/NEZHA-PyTorch) is the PyTorch version of NEZHA.
* [NEZHA-Gen-TensorFlow](https://github.com/avs-abhishek123/NLP-projects/tree/master/NEZHA-Gen-TensorFlow) provides two GPT models. One is Yuefu (乐府), a Chinese Classical Poetry generation model, the other is a common Chinese GPT model.
* [TinyBERT](https://github.com/avs-abhishek123/NLP-projects/tree/master/TinyBERT) is a compressed BERT model which achieves 7.5x smaller and 9.4x faster on inference.
* [TinyBERT-MindSpore](https://github.com/avs-abhishek123/NLP-projects/tree/master/TinyBERT-MindSpore) is a MindSpore version of TinyBERT.
* [DynaBERT](https://github.com/avs-abhishek123/NLP-projects/tree/master/DynaBERT) is a dynamic BERT model with adaptive width and depth.
* [BBPE](https://github.com/avs-abhishek123/NLP-projects/tree/master/BBPE) provides a byte-level vocabulary building tool and its correspoinding tokenizer.
* [PMLM](https://github.com/avs-abhishek123/NLP-projects/tree/master/PMLM) is a probabilistically masked language model. Trained without the complex two-stream self-attention, PMLM can be treated as a simple approximation of XLNet.
* [TernaryBERT](https://github.com/avs-abhishek123/NLP-projects/tree/master/TernaryBERT) is a weights ternarization method for BERT model developed under PyTorch.
* [TernaryBERT-MindSpore](https://github.com/avs-abhishek123/NLP-projects/tree/master/TernaryBERT-MindSpore) is the MindSpore version of TernaryBERT.
* [HyperText](https://github.com/avs-abhishek123/NLP-projects/tree/master/HyperText) is an efficient text classification model based on hyperbolic geometry theories.
* [BinaryBERT](https://github.com/avs-abhishek123/NLP-projects/tree/master/BinaryBERT) is a weights binarization method using ternary weight splitting for BERT model, developed under PyTorch.
* [AutoTinyBERT](https://github.com/avs-abhishek123/NLP-projects/tree/master/AutoTinyBERT) provides a model zoo that can meet different latency requirements.
* [PanGu-Bot](https://github.com/avs-abhishek123/NLP-projects/tree/master/PanGu-Bot) is a Chinese pre-trained open-domain dialog model build based on the GPU implementation of [PanGu-α](https://github.com/avs-abhishek123/NLP-projects/tree/master/PanGu-α).
* [CeMAT](https://github.com/avs-abhishek123/NLP-projects/tree/master/CeMAT) is a universal sequence-to-sequence multi-lingual pre-training language model for both autoregressive and non-autoregressive neural machine translation tasks.
* [Noah_WuKong](https://github.com/avs-abhishek123/NLP-projects/tree/master/Noah_WuKong) is a large-scale Chinese vision-language dataset and a group of benchmarking models trained on it.
* [Noah_WuKong-MindSpore](https://github.com/avs-abhishek123/NLP-projects/tree/master/Noah_Wukong-MindSpore) is a MindSpore version of Noah_WuKong.
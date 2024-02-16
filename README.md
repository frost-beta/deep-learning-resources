# Resources for learning Deep Learning 

Here are some resources for learning Deep Learning as a mediocre programmer.

## The d2l Book

I found it best getting started by reading the [Dive into Deep Learning](https://d2l.ai) book, which is comprehensible and has enough depth and breadth.

## Math

I met various math concepts in d2l constantly, some were new to me, and some were things I learnt at school but never touched then for more than 10 years. Below are some sites explaining math very well, even make you love math!

- [Math is Fun](https://www.mathsisfun.com)
- [Better Explained](https://betterexplained.com)

If you found matrices still too hard to understand, following lecture notes might help you as they helped me.

- [Matrix algebra for beginners](https://vcp.med.harvard.edu/papers/matrices-1.pdf) ([archive](https://web.archive.org/web/20240112194052/https://vcp.med.harvard.edu/papers/matrices-1.pdf))
- [Gradients involving matrices](https://web.stanford.edu/class/math114/lecture_notes/gradients_involving_matrices.pdf) ([archive](https://web.archive.org/web/20240203013220/https://web.stanford.edu/class/math114/lecture_notes/gradients_involving_matrices.pdf))

## Articles

Many ideas in d2l are hard to understand, which is normal because it tries to explain and implement complex ideas in a short chapter. I struggled to build intuitions for some important ideas and below are some great articles that helped me a lot.

### Basics

- [Understanding softmax and the negative log-likelihood](https://ljvmiranda921.github.io/notebook/2017/08/13/softmax-and-the-negative-log-likelihood/) ([archive](https://web.archive.org/web/20231224030853/https://ljvmiranda921.github.io/notebook/2017/08/13/softmax-and-the-negative-log-likelihood/))
- [What is torch.nn really?](https://pytorch.org/tutorials/beginner/nn_tutorial.html) ([archive](https://web.archive.org/web/20231205022718/https://pytorch.org/tutorials/beginner/nn_tutorial.html))
- [Softmax Temperature](https://medium.com/mlearning-ai/softmax-temperature-5492e4007f71) ([archive](https://archive.is/vZnjH))

### Encoder-Decoder

- [Understanding LSTM Networks](https://colah.github.io/posts/2015-08-Understanding-LSTMs/) ([archive](https://web.archive.org/web/20240131082018/https://colah.github.io/posts/2015-08-Understanding-LSTMs/))
- [Encoder-Decoder Seq2Seq Models, Clearly Explained](https://medium.com/analytics-vidhya/encoder-decoder-seq2seq-models-clearly-explained-c34186fbf49b) ([archive](http://archive.today/PMVF1))

### Attention

- [Visualizing A Neural Machine Translation Model (Mechanics of Seq2seq Models With Attention)](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/) ([archive](https://web.archive.org/web/20240206032804/https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/))
- [Understanding and Coding the Self-Attention Mechanism of Large Language Models From Scratch](https://sebastianraschka.com/blog/2023/self-attention-from-scratch.html) ([archive](https://web.archive.org/web/20240114155142/https://sebastianraschka.com/blog/2023/self-attention-from-scratch.html))

### Transformer

- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) ([archive](https://web.archive.org/web/20240210055201/http://jalammar.github.io/illustrated-transformer/))
- [The Random Transformer](https://osanseviero.github.io/hackerllama/blog/posts/random_transformer/) ([archive](https://web.archive.org/web/20240210054909/https://osanseviero.github.io/hackerllama/blog/posts/random_transformer/))
- [Transformer Architecture: The Positional Encoding](https://kazemnejad.com/blog/transformer_architecture_positional_encoding/) ([archive](https://web.archive.org/web/*/https://kazemnejad.com/blog/transformer_architecture_positional_encoding/))

### Embedding

- [Sentence Embeddings. Introduction to Sentence Embeddings](https://osanseviero.github.io/hackerllama/blog/posts/sentence_embeddings/) ([archive](https://web.archive.org/web/20240208144837/https://osanseviero.github.io/hackerllama/blog/posts/sentence_embeddings/))
- [How to generate text: using different decoding methods for language generation with Transformers](https://huggingface.co/blog/how-to-generate) ([archive](https://web.archive.org/web/20240125075747/https://huggingface.co/blog/how-to-generate))

### Rotary Positional Encoding

- [Understanding Rotary Positional Encoding](https://medium.com/@ngiengkianyew/understanding-rotary-positional-encoding-40635a4d078e) ([archive](https://archive.is/Cdc9y))
- [Why Are Sines and Cosines Used For Positional Encoding?](https://mfaizan.github.io/2023/04/02/sines.html) ([archive](https://web.archive.org/web/20230419142252/https://mfaizan.github.io/2023/04/02/sines.html))
  - [Complex Number Primer - Polar & Exponential Form](https://tutorial.math.lamar.edu/Extras/ComplexPrimer/Forms.aspx) ([archive](https://web.archive.org/web/20240212093309/https://tutorial.math.lamar.edu/Extras/ComplexPrimer/Forms.aspx))

### LLaMA

- [LLaMA-2 from the Ground Up](https://cameronrwolfe.substack.com/p/llama-2-from-the-ground-up) ([archive](https://web.archive.org/web/20231123055809/https://cameronrwolfe.substack.com/p/llama-2-from-the-ground-up))
- [Understanding Llama2: KV Cache, Grouped Query Attention, Rotary Embedding and More](https://ai.plainenglish.io/understanding-llama2-kv-cache-grouped-query-attention-rotary-embedding-and-more-c17e5f49a6d7) ([archive](https://archive.is/Sqmci))
- [SwiGLU](https://kikaben.com/swiglu-2020/) ([archive](https://web.archive.org/web/20240105225430/https://kikaben.com/swiglu-2020/))

Following LLaMA2 implementations in PyTorch are very similar, but their code comments are kind of complementary. I find reading both side-by-side really helpful.

- [LLaMA2 from Scratch](https://github.com/aju22/LLaMA2)
- [pytorch-llama](https://github.com/hkproj/pytorch-llama)

After getting familiar with the PyTorch code, the C implementation helps understand deeper.

- [Inference Llama 2 in one file of pure C](https://github.com/karpathy/llama2.c)

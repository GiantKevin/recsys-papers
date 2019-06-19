# Paper Study

## Word Embedding

### Analogies Explained: Towards Understanding Word Embeddings

- 动机

  解释了为什么通过pairwise的词共现信息，可以训练出woman is to queen as man is to king和 $w_{a^*}-w_a+w_b=w_{b^*}$这样的属性。

- 定义

  - PMI
  - Paraphrase

- 从PMI的角度解释了为什么$W\ne C$

  如果$W=C$的话，$W^TW=PMI$需要PMI是半正定的，对于通常的语料库不现实。所以说这是一个不必要的constraint，并且有可能会使低秩逼近效果变差。

- 
### Analogies Explained: Towards Understanding Word Embeddings

- 动机

  解释了为什么通过pairwise的词共现信息，可以训练出woman is to queen as man is to king和w_a*-w_a+w_b=w_b*这样的属性。

- 定义

  - PMI
  - Paraphrase

- 从PMI的角度解释了为什么不能用W=C

  如果W=C的话，W‘W=PMI需要PMI是半正定的，对于通常的语料库不现实。所以说这是一个不必要的constraint，并且有可能会使低秩逼近效果变差。

- 
# deep_learning
Projects related to traning neural nets

1) A multi layered perceptron from scratch including the back propogation [link](https://github.com/rpharale/deep_learning/blob/main/notebooks/mlp_from_scratch/mlp_from_scratch.ipynb):
    - This is developed using [micrograd](https://github.com/karpathy/micrograd) as reference.
    - Video tutorial: [link](https://www.youtube.com/watch?v=VMj-3S1tku0)
    - More references: [link](https://github.com/karpathy/nn-zero-to-hero/tree/master/lectures/micrograd)
   
2) Makemore: 
    - Part 1: A Character level bigram model built using count based method and linear neural net model [link](https://github.com/rpharale/deep_learning/blob/main/notebooks/makemore/part1/makemore_part1_bigrams.ipynb):
        - References: [makemore project](https://github.com/karpathy/makemore)
        - Video tutorial: [link](https://www.youtube.com/watch?v=PaCmpygFfXo&t=1398s)
        - Notebook used in the video: [link](https://github.com/karpathy/nn-zero-to-hero/blob/master/lectures/makemore/makemore_part1_bigrams.ipynb)
    
    - Part 2: A character level laguage model which can take in more than 2 character as an input, embedds them in n-dimensional space and predicts the next character [link](https://github.com/rpharale/deep_learning/blob/main/notebooks/makemore/part2/makemore_part2_mlp.ipynb).
        - References: Bengio et al. 2003 MLP language model paper (pdf): [link](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)
        - Video tutorials: [link](https://www.youtube.com/watch?v=TCH_1BHY58I)
        - Notebook used in the video: [link](https://github.com/karpathy/nn-zero-to-hero/blob/master/lectures/makemore/makemore_part2_mlp.ipynb)
        - makemore github link: [link](https://github.com/karpathy/makemore) 
    
   - Part 3: Same character level language model which can take in 2 or more chars as an input, embeds them in n-dimensional space and predicts the next character using batch norm in a 6 layered network. It also introduces a certain diagnostic tools that can be useful for debugging [link](https://github.com/rpharale/deep_learning/blob/main/notebooks/makemore/part3/makemore%20Part3%20Batch%20Norm.ipynb).
       - Video tutorial: [link](https://www.youtube.com/watch?v=P6sfmUTpUmc)
       - Notebook used in the video: [link](https://github.com/karpathy/nn-zero-to-hero/blob/master/lectures/makemore/makemore_part3_bn.ipynb)
   
   - Part 4: Same as Part 3 but replace the loss.backward() call from Pytorch and implemnt your own back propogation code. Fun and involved exercise with a lot of tensor differentiation. [link](https://github.com/rpharale/deep_learning/blob/main/notebooks/makemore/part4/makemore_part4_manual_backprop.ipynb)
       - Video tutorial: [link](https://www.youtube.com/watch?v=q8SA3rM6ckI)
       - Notebook used in the video: [link](https://github.com/karpathy/nn-zero-to-hero/blob/master/lectures/makemore/makemore_part4_backprop.ipynb)
      
3) NLP:
    - Character level language models: 
        -> Names classifier with simple RNN model built from scratch in Pytorch: [link](https://github.com/rpharale/deep_learning/blob/main/notebooks/nlp/char_level_models/names_classifier/names_classifier.ipynb)
   
4) Alogrithms:
    - Perceptron:
        -> Perceptron code to classfy the 2-dimensional data with 2 classes. \
           Numpy based code: [link](https://github.com/rpharale/deep_learning/blob/main/notebooks/algorithms/perceptron/perceptron_numpy.ipynb) \
           Pytorch based code: [link](https://github.com/rpharale/deep_learning/blob/main/notebooks/algorithms/perceptron/perceptron_pytorch.ipynb)
        

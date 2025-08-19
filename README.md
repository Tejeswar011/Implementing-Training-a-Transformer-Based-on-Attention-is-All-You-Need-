# Implementing-Training-a-Transformer-Based-on-Attention-is-All-You-Need-
Implemented a Transformer architecture from scratch based on seminal "Attention is all you need" paper demonstrating expertise in advanced neural architecture design using Pytorch. optimizing hyperparameters to achieve BLUE score improvement of 15% over baseline performance.  

Embedding Layer: It Embeds all the input words given and assign weights to the Tokens based on their importance in the context. Imagine a look up table where all the words are assigned certain weights with respect to all other words.

Positional Embedding: As the model has certain Context_Length  it is required to remember all the positions of each token to predict the next token.
                     E.g., Dog is cute
                           Dog=1, is =2, cute=3
                           

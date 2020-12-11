## CS626 Speech and Natural Language Processing and the Web: Project
**Efficient Neural Machine Translation**  
Anshul Tomar 170070007  
Anwesh Mohanty 170070009  
Parth Shettiwar 170070021   

Code Base:  
The Folder contains 2 .ipynb files.  
1)Ours.ipynb  : Our NMT Model based on RNNsearch with adverserial training and noise added to avoid overfitting.  
2)Transformer.ipynb  : This model is based on **All you need is Attention** paper. We have ran the transformer on Multi30k Dataset.  
To run them, just upload them on a collab notebook, and run all cells.    
Both models have been trained on Multi30k English-German Dataset. The final block computes the Bleu score in each. The training is done for 10 epochs and can  
be changed in the training bloch by varying the parameter N_EPOCHS.

The basic architecture of code consists of following:    
1)Encoder: Consists of an Embedding layer, bi-directional GRU and a Linear layer     
2)Attention Layer: A feedforward neural network to implement attention  
3)Decoder: Consists of an Embedding layer, GRU and a Linear layer   

Following are some of the attention maps generated for our model:  





 

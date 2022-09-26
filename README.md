# Spam-filter-for-Quora-questions

**Glove Embedding Pre-Trained Model**:
Link : http://nlp.stanford.edu/data/glove.42B.300d.zip

Model:
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 text_input (InputLayer)     [(None, 44)]              0         
                                                                 
 embedding (Embedding)       (None, 44, 300)           58841100  
                                                                 
 lstm (LSTM)                 (None, 512)               1665024   
                                                                 
 dropout (Dropout)           (None, 512)               0         
                                                                 
 dense (Dense)               (None, 256)               131328    
                                                                 
 dropout_1 (Dropout)         (None, 256)               0         
                                                                 
 dense_1 (Dense)             (None, 128)               32896     
                                                                 
 dense_2 (Dense)             (None, 25)                3225      
                                                                 
 dropout_3 (Dropout)         (None, 25)                0         
                                                                 
 dense_3 (Dense)             (None, 1)                 26        
                                                                 
=================================================================
Total params: 60,673,599
Trainable params: 1,832,499
Non-trainable params: 58,841,100
_________________________________________________________________

**ROC_AUC Score : 0.9660**




# Gender Classification Using Deep Learning

## Deep learning models 

Models: ![CNN](https://github.com/roscibely/Gender-Classification/blob/main/models/CNN_model.ipynb), ![MLP](https://github.com/roscibely/Gender-Classification/blob/main/models/DNN_model.ipynb), ![RNN](https://github.com/roscibely/Gender-Classification/blob/main/models/RNN_model.ipynb), ![BiLSTM](https://github.com/roscibely/Gender-Classification/blob/main/models/BiLSTM_model.ipynb), ![GRU](https://github.com/roscibely/Gender-Classification/blob/main/models/GRU_model.ipynb). 

Usage is simple. 

    testename = prepare_encod_names({"cibely"})   # name are encod as a vector of numbers
    resu=(LSTMmodel.predict(testename) > 0.5).astype("int32")
    if int(resu)==1:
      print('M')
    else:
      print('F')
      
    out: F

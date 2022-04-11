# snaccit (Bert pretrained Model Question Answers)
## Requirements
To be able to execute this code, you need to fulfill the following requirement:  
&nbsp;&nbsp; 1- Python >= 3.5 (In our example we have used Python 3.6)  
&nbsp;&nbsp; 2- Tensorflow >= 1.10 (In our example we have used Tensoflow 1.13)  
&nbsp;&nbsp; 3- Install the bert-as-service via pip with the following Commands:  
&nbsp;&nbsp;&nbsp;&nbsp; a) `pip install bert-serving-server`   
&nbsp;&nbsp;&nbsp;&nbsp; b) `pip install bert-serving-client`    
&nbsp;&nbsp; 4- Download the Pre-trained Bert Model, available in the follwing Link :point_right: [model link](https://bert-as-service.readthedocs.io/en/latest/section/get-start.html)     
:warning: We have used in our example "the uncased_L-12_H-768_A-12" Model.  
&nbsp;&nbsp; 5- Run the server with the following command to be able to use the server:    
&nbsp;&nbsp;&nbsp;&nbsp; a) `bert-serving-start -model_dir /path/english_L-12_H-768_A-12/ -num_worker=1`   
&nbsp;&nbsp;&nbsp;&nbsp; b) Let the server running in the command line    
&nbsp;&nbsp; 6- You will only need to run the **model_train.py** script.  
:warning: You need to give an **absolute path** (for example: C:/Users/Maha/uncased_L-12_H-768_A-12/uncased_L-12_H-768_A-12) in the model_dir parameter = the path of the downloaded model in Step 4    
PS :star2: : Make sure the have the following libraries: pandas, re, gensim, scikit-learn :smiley:    

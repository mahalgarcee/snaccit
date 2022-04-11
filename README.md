# snaccit
Machine Learning Code

To be able to execute this code, you need to fulfill the following requirement:
1- Python >= 3.5 (In our example we have used Python 3.6)
2- Tensorflow >= 1.10 (In our example we have used Tensoflow 1.13)
3- Install the bert-as-service via pip with the following Commands:
    a) pip install bert-serving-server
    b) bert-serving-client
4- Download the Pre-trained Bert Model, available in the follwing Link:
    a) https://bert-as-service.readthedocs.io/en/latest/section/get-start.html
PS: We have used in our example "the uncased_L-12_H-768_A-12" Model.
5- Run the server with the following command to be able to use the server:
    bert-serving-start -model_dir /path/english_L-12_H-768_A-12/ -num_worker=1
6- You will only need to run the model_train.py script.
PS: You need to give an absolute path in the model_dir parameter = the path of the downloaded model in Step 4
Another PS: Make sure the have the following libraries: pandas, re, gensim, scikit-learn
# Next-Word-Prediction
This is a Natural Language Processing and Deep Learning-based project where we are predicting the next word of the sentence.

The dataset file is moby.txt which is of 1.3 MB and after preprocessing, it contains around 1.23 Million words. We first prepare the dataset from the raw corpus of text. We use the first 25 words as features and then 26th ford as a label. Similarly, we pass the while raw corpus of text. As i've trained the model on Google Colab for faster training so you are advised to use the same and upload the moby.txt file on colab first when we are using 'files.upload()' command in the code.

I've used a basic LSTM based neural network with 256 batch size and run the model for 350 epochs. Then we are saving the model and the vocabulary using pickle.

Kindly let me know if you found any doubts in understanding or implementing the code.

LinkedIn: https://www.linkedin.com/in/ashish-jangra/ OR Website: http://www.ashishjangra.com

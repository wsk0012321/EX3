### This project is an evaluation of the art-of-the-state metaphor identification algorithm DeepMet. For more information, please check their page:
####     https://github.com/YU-NLPLab/DeepMet
### to intall requirements:
####     pip install -r requirements.txt
### We merged the filtration of test data and evaluation on one notebook. Step 1 and 2 are intended for creating test data. Step 3(1) uses the pre-trainedm model to do predict, but for efficiency we highly recommend to start at 3(2). We have provided the prediction and test data. In case you need to use our pre-trained model for step(1), you can download it to the folder where the script is stored:
####     [https://drive.google.com/file/d/1-Ahy7mWKr95gFt6jbPwV_2Ziz5NnBn3Y/view](https://drive.google.com/file/d/1-B3jlRA_JIy-2vQQR4OWQnKdqoaYaYi6/view?usp=sharing)
### The model is trained with original version of DeepMet-vua.py on VUAMC corpus with the following parameters:
#### max length = 128, batchsize = 64, dropout rate = 0.1, n-fold = 2, hidden size = 768, random state = 2020, validation split = 0.2, learning rate = 2e-5, epochs = 3
### For compatibility, it is advisable to use Python 3.9.

# Deep_Learning_Challenge


## Report on the Neural Network Model
A report on the performance of the deep learning model created for AlphabetSoup.

### Overview of the analysis: Explain the purpose of this analysis.
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. This analysis therefore uses my knowledge of machine learning and neural networks, to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.


### Results: Using bulleted lists and images to support your answers, address the following questions.
#### What variable(s) are the target(s) for your model?
**IS_SUCCESSFUL**— Was the money used effectively? - this is the target variable for my model. 

#### What variable(s) are the features for your model?
![image](https://user-images.githubusercontent.com/99673859/183854453-9f2e4bdf-7bf4-42be-bf50-3c6dc2b199d9.png)

#### What variable(s) should be removed from the input data because they are neither targets nor features?
EIN and NAME—Identification columns 


### Compiling, Training, and Evaluating the Model
#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
My first model had 2 hidden layers 80 and 30 neuron respectively and relu activation on both hidden layers why sigmoid activation was employed for the output layer. 
![image](https://user-images.githubusercontent.com/99673859/183852849-4632b8a6-8651-4149-bb36-618b6088f851.png)

#### Were you able to achieve the target model performance?
No. My model at best gave a 73.3% accuracy 1.7% less than the target model performance
![image](https://user-images.githubusercontent.com/99673859/183855525-605d10cc-b385-4ae3-9d74-076ea883cf9e.png)

#### What steps did you take in your attempts to increase model performance?
To Increase model performance i tried optimising the model in two ways. 
1) I increased the number of epochs to the training regimen. This resulted in an accuracy of 73.4%
![image](https://user-images.githubusercontent.com/99673859/183852557-157a5b83-86f7-4c88-9c14-8ce5c3bf2e17.png)
![image](https://user-images.githubusercontent.com/99673859/183855675-7d71034d-0be9-4e63-9a4c-a30cc6339782.png)

2) I then tried using differnt activation functions (tanh) for the hidden layers. Accuracy was 73.1%
![image](https://user-images.githubusercontent.com/99673859/183852391-19eac528-7970-4f74-abad-7b566b60932b.png)
![image](https://user-images.githubusercontent.com/99673859/183855863-96a1ad8f-a943-40a6-8f7c-ee4620a76f3c.png)


### Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
Overall, I beleieve that the model will successfull help Alphabet Soup make better choices with their lending (albeit not reaching the recommended performance. Howeevr to improve the model performance, we could explore other machine learning techniques and tools. This should mostly be aimed at reducing the noise in the data, thus pointing us in the direction of a better performning model.

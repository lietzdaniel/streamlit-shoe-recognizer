# streamlit-shoe-recognizer
This streamlit application was built by training the model set up in [this](https://github.com/lietzdaniel/shoe-recognizer) repository. It has the goal of classifying the model of the sneaker in the image uploaded by the user. 

##Functionality 
The streamlit application can be accessed [here](https://lietzdaniel-streamlit-shoe-recognizer-frontendstreamlit-bvk8g6.streamlit.app/).
To use it, you simply upload an image with a sneaker in the designated button. After the image is loaded, use the Classify button in order for the Machine Learning model to classify your shoe. After a few seconds, the predicted shoe with a probability will be displayed. An example can be seen here: ![Alt Text](https://i.imgur.com/vIVYUMv.gif)

##Reflection & Future Thoughts: 
On the popular shoe versions, the model seems to be working quite well, but only if they are laid out straight on the ground. Especially with rotations and vertical images, a bad performance can be observed. In future updates of the model, I will add rotation to the training set and increase the training set size in order to improve the model.
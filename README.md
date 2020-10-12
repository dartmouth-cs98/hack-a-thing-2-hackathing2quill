# hack-a-thing-2-hackathing2quill
hack-a-thing-2-hackathing2quill created by GitHub Classroom

## What did I make?
- In order to more deeply orient myself with the implementation and deployment of federated machine learning models, I did a deep dive into a 10 hour joint pytorch and pysyft tutorial. Pytorch is a python machine-learning model built off of the torch library that allows programmers to build and implement class-like machine learning models. The tutorial focused more on implementation than theory, a quality I appreciated given my background in more conceptual deep learning. The tutorial focused on creating individual task-specific models to address a few large classification problems. Most notably, I created, tuned, visualized, and deployed an image recognition model. The tutorial is created by DeepLizard.com, and is a 10-hour youtube series. 

- I spent **10 hours** following the steps and instructions in the tutorial
- I spent **2-4 hours** taking concepts from the tutorials and implementing them on my own
- I spent **2 hours** learning how pysyft implements pytorch models in a federated way. 
- I wrote over **4,000 lines** of Jupyter Notebook code

## What did I learn?
- I learned a tremendous amount about object-oriented machine learning. Easily the most valuable knowledge from this course is how to create and train models with pytorch, the framework upon which pysyft is built. 
- I also reinforced some important federated learning and deep learning concepts. Such concepts include tensor algebra, training models on distributed datasets, model quality assessments (confusion matrices), and network training with GPUs. 
- I learned that building models is easy, but training them to be accurate is difficult. I think this raises some interesting questions for our Artificien team to answer; for example, the data I used in the tutorials is clean and evenly distributed. Given that we will be democratically sourcing our data from app users, it's important to consider how the balancing and biases of our federated datasets may differ from the needs of our corporate or institutional clients. 

## How does this relate to my project?
- The reason I chose this Pytorch tutorial in particular (and not Tensorflow, like last time) is that Pytorch is the framework upon which PySyft is built, meaning that any client models we choose to deploy in our app will require us to understand Pytorch. Pysyft is the federated learning library that we will be implementing our project with. We chose PySyft over TensorflowFederated because PySyft is deployable and can be used in an actual product. TFF is currently just an advanced local learning tool. 
- Federated machine learning is the basis of our project. In short, our business model is to take untrained algorithms from clients and train them in a federated way on consumer data from a wide and diverse net of device users and wearers. This data remains on the user's phone so as to maximally respect current privacy laws and future norms, meaning that it is the model that gets passed between us and the user. This requires an intimate knowledge of the federated learning library PySyft, built upon PyTorch. Since I am not a strong mobile developer, I plan to make myself most useful in this exchange process by learning how to train and deploy models with PyTorch. 

## What didn't work?
- I felt like the pace of the tutorial was all over the place. Certain video segments, like **#26 - CNN training with example** and **#17 - Object Oriented Neural Networks** really quickly got at the heart of what I was looking for out of my hack-a-thing 2. Not so much "what is a tensor" or "what is an activation function" (I know these things), but "how do I take those concepts and turn them into a workable, movable model. I loved those videos, but others such as **25 - Neural Network Debugging Session** were laborious and probably not worth my time. 

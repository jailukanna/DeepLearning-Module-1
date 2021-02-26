# DeepLearning-Module-1


# What is Deep Learning?

 __Deep Learning__ is a specific subfield of machine learning.Deep learning is a mathematical framework for learning representations from data. A new take on learning representations from data that puts an emphasis on learning successive layers of increasingly meaningful representations.How many layers contribute to a model of the data is called the depth of the model.In deep learning these layered representations are almost always learned via models called neural networks, structured in literal layers stacked on top of each other.


# Why is Deep Learning important today?

Today, we enjoy the benefits of algorithms and strategies that we did not have 20 or 30 years ago, which enable us to have amazing applications that are changing lives. Allow me to summarize some of the great and important things about deep learning today:

1. ### Training in Mini-Batches :
     
     ```This strategy allows us today to have very large datasets and train a deep learning model little by little. In the past, we would have to load the entire dataset into memory, making it computationally impossible for some large datasets. Today, yes, it may take a little longer, but we at least can actually perform training on finite time. ```

2. ### Novel Activation Functions : 
     
     ```Rectified linear units (ReLUs), for example, are a relatively new kind of activation that solved many of the problems with large-scale training with backpropagation strategies. These new activations enable training algorithms to converge on deep architectures when, in the past, we would get stuck on non-converging training sessions that would end up having exploding or vanishing gradients.```

3. ### Novel Neural Network Architectures : 
      
      ```Convolutional or recurrent networks, for example, have been transforming the world by opening the possibilities of things we can do with neural networks.Convolutional networks are widely applied in computer vision applications or other areas in which the convolution operation is a natural thing to do, for example, multi-dimensional signal or audio analysis. Recurrent neural networks with memory are widely used to analyze sequences of text, thus enabling us to have networks that understand words, sentences, and paragraphs, and we can use them to translate between languages, and many more things.```

4. ### Interesting Loss Functions :
       
      ```These losses play an interesting role in deep learning because, in the past, we only used the same standard losses over and over again; losses such as the MSE. Today, we can minimize the MSE and, at the same time, minimize the norm of the weights or the output of some neurons, which leads to sparser weights and solutions that, in turn, make the produced model much more efficient when it is deployed into production.```

5. ### Novel Strategies Resembling Biology :
     
     ```Things such as missing or dropping connections between neurons, rather than having them fully connected all the time, is more realistic, or comparable to biological neural network design. Also, dropping or removing neurons altogether is a new strategy that can push some neurons to excel when others are removed, learning richer representations, while at the same time reducing the computations during training and when deployed. The sharing of parameters between different and specialized neural networks also has proven to be interesting and effective today.```

6. ### Adversarial Training : 
   
   ```Making a neural network compete against another network whose sole purpose is to generate fraudulent, noisy, and confusing data points trying to make the network fail has proven to be an excellent strategy for networks to learn better from the data and be robust against noisy environments when deployed into production. ```
        
There are many other interesting facts and points that make deep learning an exciting area and justify the writing of this Repo. I hope you are as excited as we all are and begin reading this repo knowing that we are going to code some of the most exciting and incredible neural networks of our time. Our ultimate purpose will be to make deep neural networks that can generalize.

```Generalization is the ability of a neural network to correctly make predictions on data that has never been seen before. This is the ultimate purpose of all machine and deep learning practitioners, and requires a great deal of skill and knowledge of the data.```

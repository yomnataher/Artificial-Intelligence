I'm very happy to share my second task from my training in SYNC INTERN'S as an artificial intelligence internship 💥
✳ We have data and we want to build a model to teach this data to differentiate between lines, and here we will use data for numbers to learn by them and to be able to differentiate between them, whatever the shape of these numbers. Therefore, this learning will be on images. We will build a model for learning on these images, and the result will be with the best Accuracy. 🚀

✳ The data set consists of pictures of numbers but but in different shapes. 📑

✔ From Kaggle : https://www.kaggle.com/competitions/digit-recognizer/data

✳ The Model : I used 2 models to reach the best Accuracy in the end.

       ⏩ The First Model:

              ✔ ReLU : it is a piecewise linear function that outputs the input             
                       directly if it is positive, otherwise it outputs zero. It is one of the most popular activation functions for 
                       deep learning neural networks because it has some advantages over other activation functions, such as:

        ➕ It is easy to compute and has a simple gradient.

        ➕ It helps to overcome the vanishing gradient problem, which occurs when the gradients of the activation functions become very small and prevent the network from learning effectively.

        ➕ It introduces non-linearity into the model, which allows the network to learn complex mappings between inputs and outputs.

              ✔Softmax : is an activation function that is often used in the output layer of a neural network for multiclass classification problems. It transforms the raw outputs of the network into a vector of probabilities that sum up to one. 

        ➕ It normalizes the output to a probability distribution, which makes it easier to interpret and compare the predictions.

        ➕ It is differentiable, which means it can be used with gradient-based optimization methods.

        ➕ It is invariant to scaling, which means multiplying all the elements of the input vector by a constant does not change the output.


       ⏩ The Second Model:

              ✔ I have defined two convolutional layers, two dropout layers, and two fully connected layers. The convolutional layers use a 3x3 kernel. The dropout layers randomly zero out some of the input features with a probability of 0.25 and 0.5, respectively. 
                The fully connected layers have 128 and 10 output features, respectively.The forward method defines the forward pass of the neural network, followed by a ReLU activation function. Then you apply the second convolutional layer, 
                followed by another ReLU activation function. Then you apply a max pooling layer with a 2x2 kernel

✳ The accuracy of our 2 models is

      ⏩ The First Model:

           🔴 Test Loss: 0.0198

           🔴 Test Accuracy: 99.39 %

      ⏩ The First Model:

           🔴 Test Loss: 0.06

           🔴 Test Accuracy: 98.0 %

#syncinterns #python #Artificial_Intelligence #machinelearning #pytorch #numpy #pandas #sklearn

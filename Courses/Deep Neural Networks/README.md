# Deep Neural Network Notes
## 3. The Stochastic Gradient Descent:
- ### The training graph using the *adam* optimizer
![image](https://github.com/SonuAlex/Kaggle-Courses-and-Competition/assets/90763758/e91e7742-cb8c-4f77-83a9-15b2611b32ce)
- ### The decrease in loss wih the change in batch_size and learning rate
![Graph of learning rate of the SGD model](https://github.com/SonuAlex/Kaggle-Courses-and-Competition/assets/90763758/48fe59ca-f819-4efe-87f2-5711476dd812)

(In the graph, total_data = 256, batch_size = 128, learning_rate = 0.05)

- Here we are to observe that **learning rate** is similar to the speed at which the model learns so if we were to reduce the *learning rate* the we will see that the model take longer to learn and if we increase the learning speed the model might learn quicker but won't be able to reduce the training loss.
- The **batch_size** is the number of data the model takes to correct itself. Here we see that the *bright red* dots are the batches take at that particular time and the *dull red* dots are the total data available in the training dataset.


## 4. Overfitting and Underfitting:
![image](https://github.com/SonuAlex/Kaggle-Courses-and-Competition/assets/90763758/bfda45e3-1f10-4158-975e-49aef399d076)

(This is graph shows overfitting)


![image](https://github.com/SonuAlex/Kaggle-Courses-and-Competition/assets/90763758/10c3bf18-bcf2-4dcf-b9d7-0c2c5a96749b)

- In this graph we have applied the early stopping method such that when the change in loss is less than a given value(here it is 0.001) it will stop and go back to the best weights too.
- This is a method we use to stop the model from overfitting.

## 5.Dropout and Batch Normalizations:
### Dropout:
![a86utxY](https://github.com/SonuAlex/Kaggle-Courses-and-Competition/assets/90763758/b45c29d0-c757-4b0d-9b45-614fa53d6f41)

  One of the problems that may occur when configuring a model is that we may add too many nodes to it and which may also cause overfitting. To overcome this we remove out nodes that to reduce Overfitting

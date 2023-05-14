# Deep Neural Network Notes
## 3. The Stochastic Gradient Descent:
- ### The training graph using the *adam* optimizer
![image](https://github.com/SonuAlex/Kaggle-Courses-and-Competition/assets/90763758/e91e7742-cb8c-4f77-83a9-15b2611b32ce)
- ### The decrease in loss wih the change in batch_size and learning rate
![Graph of learning rate of the SGD model](https://github.com/SonuAlex/Kaggle-Courses-and-Competition/assets/90763758/48fe59ca-f819-4efe-87f2-5711476dd812)

- Here we are to observe that **learning rate** is similar to the speed at which the model learns so if we were to reduce the *learning rate* the we will see that the model take longer to learn and if we increase the learning speed the model might learn quicker but won't be able to reduce the training loss.
- The **batch_size** is the number of data the model takes to correct itself. Here we see that the *bright red* dots are the batches take at that particular time and the *dull red* dots are the total data available in the training dataset.

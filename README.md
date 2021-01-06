Below we define a new activation function that coverage faster than swish on the cifar-10 dataset in a simple CNN model.

Relu epoch 10 -> loss: 0.2680 - accuracy: 0.9071

Swish epoch 10 -> loss: 0.8646 - accuracy: 0.6987

Custom epoch 10 -> loss: 0.1428 - accuracy: 0.9499

Relu
Loss: 0.9479744793534279
Accuracy: 0.796999990940094

Swish
Loss: 1.6475953691482543
Accuracy: 0.5329999923706055

Custom
Loss: 0.9692827097415924
Accuracy: 0.7893999814987183

By using cifar-10 as a simplpe example, relu has a accuracy since cifar-10 dataset is not as complicated as other dataset
in the future, we will compare the different on different CNN model on different datasets

By changing alpha, belta and gamma, we can create activation function that fits in different use case.

Accuracy comparsion

![alt text](https://github.com/justinkwan1216/Activation_loss/blob/master/accuracy.png)

Accuracy comparsion

![alt text](https://github.com/justinkwan1216/Activation_loss/blob/master/loss.png)

Custom activation function(beta=2,alpha=0.5,gamma=20) and swish graph(belta=1)

![alt text](https://github.com/justinkwan1216/Activation_loss/blob/master/graph.png)

the below activation function will be furthur exploded for replacement of neural network that takes negative rewards
![alt text](https://github.com/justinkwan1216/Activation_loss/blob/master/graph_2.png)

Inspired at 2020 April

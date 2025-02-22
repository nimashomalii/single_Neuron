# single_Neuron
I generated a batch of data along with their labels, where points inside a circle of radius one are labeled as 1, and points outside the circle are labeled as 0. Then, I attempted to train a single neuron to learn these labels—almost like magic. Enjoy my code!

Our model, which is designed for labeling, consists of only a single neuron.
On the other hand, the input to our model (the single neuron) is two-dimensional, which we have plotted on a 2D plane.
Red indicates labels of 1, while blue represents labels of 0.

![image](https://github.com/user-attachments/assets/e221e704-452f-46ce-9529-ea97b7fa01b0)
As I mentioned, each input data point has two features. Therefore, our neuron will have three trainable parameters: two weights for the inputs and one bias.
As you know, if a neuron only receives the raw input data, it can act as a linear separator and separate the data by drawing a straight line between them.
In the code I wrote, I built a neuron with two inputs and one bias to train on this data. However, as expected, it did not train effectively—it can only separate the data linearly and is unable to distinguish the circular boundary.
![image](https://github.com/user-attachments/assets/ce4829d9-15ab-4c82-9dbf-0b6d1bbd774e)

Below is the graph of the loss function with respect to the epochs. Even after 10,000 training iterations, the loss has remained nearly the same as before.

![image](https://github.com/user-attachments/assets/f954c2ad-2f67-4e2e-9ec7-1f835dc6435b)


![image](https://github.com/user-attachments/assets/cfcaf1c4-ad82-4dc9-90e5-120545072cec)

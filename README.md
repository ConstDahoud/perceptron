# Perceptron
## 1. What is perceptron?
The perceptron is one of the simplest artificial neural nets developed by Frank Rosenblatt in 1958 and is an algorithm that make one output from numerous inputs whose each connection is associated with values in the weight vector. The perceptron is called TLU(Threshold logic unit) or sometimes LTU(Linear threshold unit), it works similarly to the way neurons consisting of human brain work. More details in [Perceptron_Wikipedia](https://en.wikipedia.org/wiki/Perceptron)

## 2. The structure of single perceptron
![01_structure_of _single_perceptron](https://github.com/ConstDahoud/perceptron/blob/main/images/01_structure_of%20_single_perceptron.png)

## 3. Logical operations with perceptron
It is easy to implement logical operation such as AND, NAND, and OR using single-layer perceptron. However, It is impossible for single-layer perceptron to learn XOR operation because that is only capable of implement functions that divide one area into two areas by one line. One solution for solving this problem is combine AND, NAND, and OR operation to make XOR operation. That is, we can make it by adding a hidden layer between the input layer and the output layer. This process is called Multilayer perceptron. Refer to 01_logical_operations_with_perceptron.ipynb with these following figures.

#### AND operation with perceptron
![01_and_op_with_perceptron](https://github.com/ConstDahoud/perceptron/blob/main/images/01_and_op_with_perceptron.png)

#### XOR operation with perceptron
![01_xor_op_with_percetron](https://github.com/ConstDahoud/perceptron/blob/main/images/01_xor_op_with_percetron.png)

## 4. The structure of multilayer perceptron
The multilayer perceptron(MLP) consists of three or more layers(an input layer and an output layer with one or more hidden layers). We call it a lower layer that a layer which is close to the input layer and call it a upper layer that a layer which is close to the output layer. All layers except for the output layer in the multilayer percecptron are fully-connected including bias. More details in [Multilayer_perceptron_Wikipedia](https://en.wikipedia.org/wiki/Multilayer_perceptron)  
![02_multilayer_perceptron](https://github.com/ConstDahoud/perceptron/blob/main/images/02_multilayer_perceptron.png)

## 5. Classification with multilayer perceptron
We can use the multilayer perceptron to solve classification problems. Refer to 02_classification_with_multilayer_perceptron.ipynb with these following figures.
![02_classification_problem](https://github.com/ConstDahoud/perceptron/blob/main/images/02_classification_problem.png)
![02_multilayer_perceptron](https://github.com/ConstDahoud/perceptron/blob/main/images/02_classification_with_mlp.png)

## 6. Function approximation with multilayer perceptron
We can use the multilayer perceptron to solve function approximation problems. Refer to 03_function_approximation_with_multilayer_perceptron.ipynb with this following figure.
![03_function_approximation](https://github.com/ConstDahoud/perceptron/blob/main/images/03_function_approximation_with_multilayer_perceptron.png)

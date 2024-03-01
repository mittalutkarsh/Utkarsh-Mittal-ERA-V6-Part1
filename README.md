# Utkarsh-Mittal-ERA-V6-Part1
Utkarsh ERA V6 Part1 Backpropogation

**Screen shot of the File**
<img width="1686" alt="image" src="https://github.com/mittalutkarsh/Utkarsh-Mittal-ERA-V6-Part1/assets/36775837/c6a53dda-5710-4293-bb34-71614f08a4dc">



## Major Steps
### Input Layer

- **Nodes**: `i1`, `i2`
- **Description**: The input layer is where the network receives its input data. There are two input nodes in this network.

### Weights between Input and Hidden Layer

- **Weights**: `w1`, `w2`, `w3`, `w4`
- **Description**: Each connection between the input and hidden layer nodes has an associated weight. These weights adjust the input values as they are passed to the next layer.

### Hidden Layer

- **Nodes**: `h1`, `h2`
- **Description**: The hidden layer processes the inputs received from the input layer. It combines the weighted inputs and applies a nonlinear sigmoid activation function. The diagram  connections (`a_h1`, `a_h2`).

### Weights between Hidden and Output Layer

- **Weights**: `w5`, `w6`, `w7`, `w8`
- **Description**: These weights modulate the signals being passed to the output layer from the hidden layer.

### Output Layer

- **Nodes**: `o1`, `o2`
- **Description**: The output layer receives the processed signals from the hidden layer and generates the output of the network. Each output node represents a specific output value.

### Activation at Output

- **Activations**: `a_o1`, `a_o2`
- **Description**: These denote the activation functions applied at the output nodes, determining the final output of each node.

## Error Calculation

- **Errors**: `E1`, `E2`
- **Description**: The network calculates the error for each output node by comparing the actual output with the target output. Error formula suggests L2 Loss

### Total Error

- **Node**: `E_Total`
- **Description**: The total error of the network is calculated by summing the errors from all output nodes. This value is crucial during the training process.

## Training

The network is trained using a backpropagation algorithm to adjust the weights based on the calculated error. The goal is to minimize `E_Total` by iteratively updating the weights to improve the model's predictions.

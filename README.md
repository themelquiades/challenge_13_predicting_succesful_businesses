# Predicting Successful Businesses with Deep Neural Networks
Week 13 Challenge, using deep neural networks to predict which funding applicants will become successful businesses

## Summary of Results

Original model:

- Input features: 116
- Number of hidden layers: 2
    - Nodes in hidden layer 1: 58 (avg of inputs and output neurons)
        - Layer 1 activation: relu
    - Nodes in hidden layer 2: 29 (avg of layer 1 nodes and neurons)
        - Layer 2 activation: relu
- Number of output neurons: 1
    - Output activation: sigmoid
- Number of epochs: 50
- Test accuracy: 0.73329

Alternate model 1:

- Input features: 116
- Number of hidden layers: 2
    - Nodes in hidden layer 1: 39
        - Layer 1 activation: relu
    - Nodes in hidden layer 2: 39
        - Layer 2 activation: relu
- Number of output neurons: 1
    - Output activation: sigmoid
- Number of epochs: 50
- Test accuracy: 0.73224

Alternate model 2:

- Input features: 116
- Number of hidden layers: 3
    - Nodes in hidden layer 1: 145
        - Layer 1 activation: relu
    - Nodes in hidden layer 2: 87
        - Layer 2 activation: relu
    - Nodes in hidden layer 3: 29
        - Layer 2 activation: relu
- Number of output neurons: 1
    - Output activation: sigmoid
- Number of epochs: 50
- Test accuracy: 0.72898


As you can see from the results above, the two layer model with 58 nodes followed by 29 nodes had the best results. Adding an additional layer did not improve the model. 
    

All analysis was done using Jupyter Lab.

## Contributors

This analysis was created by Nico Cortese with support from the lovely Fintech Coding Boot Camp Team at Boot Camp Spot / Columbia School of Engineering

Nico Cortese

XXX-XXX-XXXX

XXXX@gmail.com

---

## License

MIT License

Copyright (c) 2022 NicoCortese

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
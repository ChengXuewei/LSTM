# Long Short-Term Memory

 Long Short-Term Memory (LSTM) is an advanced variant of conventional Recurrent Neural Networks (RNNs), and it plays an important role in natural language processing (NLP). LSTM is better suited to process data with long-range dependencies than vanilla RNNs, thanks to the gating mechanisms of LSTM that control the flow of information through the network. Empirical evidence suggests that LSTM can generate well in many real-world tasks, especially when combined with weight regularization, but its theory of generalization ability remains largely unexplored due to its complicated and interconnected structures. This paper provides two new generalization error bounds for LSTM based on empirical Rademacher complexity for multi-class classification tasks. The new bounds reveal how the three gates help reduce the network complexity and address the vanishing gradient problem of conventional RNNs to enable effective learning over time steps. The first error bound is built solely based on the Frobenius norms of the network weight matrices used in $L_2$ regularization to prevent overfitting and improve generalization. The second error bound is based on a mixture of the spectral norms of the weight matrices for the hidden states and the Frobenius norms of the weight matrices for the inputs, and it can potentially improve the first bound. 
 
## Main paper
Cheng X, Ma S. Generalization Bounds of Long Short-Term Memory. Submitted, 2024.

## Environment

* Numpy 1.23.5
* torch  2.5.1+cu121

## Create a virtual environment with conda

```bash
conda create -n LSTM python=3.9
conda activate LSTM
```

## Licence
- For academic and non-commercial use only
- Apache License 2.0

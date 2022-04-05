# debiasing-using-attention-regularization
Increasing Robustness to Spurious Correlations using Attention Regularization


## What is it?
In this work, we propose a new method that falls under the category of regularization-based bias mitigation methods. However, the regularization is not applied as an additional term to the objective function. It is rather applied to the attention weights that we believe are responsible for the unintended correlations. One example could be the attention weights from the token “kitchen" to the token “her", which could reflect the model's bias against feminine gender.

## How it works
 We divide the project into two phases - 1.  and 2. 

1. **Phase 1**: Finding the attention weights causing the bias.
2. **Phase 2**: Debiasing through regularizing those attention weights.

Reducing the bias in classifiers using policy gradient can be summarized as follows:

## Installation

### Python package
Clone the repository, then install the required packages as follows:

`pip -r install requirements.txt`

## Running the experiments

TBD


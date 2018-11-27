## Combining Aleatoric and Epistemic Uncertainty in One Model
Section 3. of the paper: A Kendall, Y Gal, “**What Uncertainties Do We Need in Bayesian Deep Learning for Computer Vision?**”, NIPS 2017 [arXiv](https://arxiv.org/abs/1703.04977)

Combines th loss of eq (8) and dropout at test time.


### Code

Train an autoencoder:

`
python main.py --mode train
`

Test it:

`
python main.py --mode test --checkpoint model/model
`

Visualize TensorBoard logs:

`
tensorboard --logdir logs/
`

###  Results



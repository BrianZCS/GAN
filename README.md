# GAN

## GAN-BASE_Q1.IPYNB

Update the generator  by ascending its stochastic  gradient:
$$\nabla_{\theta_{g}}  \cfrac{1}{n_{z}} \sum_{i=1}^{n_{z}}  \log D(G(z^{(i)}))\big )$$

## GAN-BASE_Q2.IPYNB

Update the generator by descending its stochastic gradient:
$$\nabla_{\theta_{g}}  \cfrac{1}{n_{z}}  \sum_{i=1}^{n_{z}}\log (1-D(G(z^{(i)})))\big )$$

## GAN-BASE_Q3.IPYNB

Add L-1 Regularization to the discriminator.

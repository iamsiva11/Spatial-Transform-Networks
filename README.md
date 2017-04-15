# Spatial Transformer Networks

Google DeepMind released an awesome paper called Spatial Transformer Networks aiming at boosting the geometric invariance of CNNs in a very elegant way.

The goal of spatial transformers is to add to your base network a layer able to perform an explicit geometric transformation on an input. The parameters of the transformation are learnt thanks to the standard backpropagation algorithm, meaning there is no need for extra data or supervision.

The use of a SPN is
* to improve classification
* to subsample an input
* to learn subparts of objects
* to locate objects in an image without supervision

Formulating Spatial transformers Three main differentiable blocks: 
* Localisation network 
* Grid generator
* Sampler



Spatial Transformer Networks
https://arxiv.org/abs/1506.02025
http://www.gitxiv.com/posts/5WTXTLuEA4Hd8W84G/spatial-transformer-networks
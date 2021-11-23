The repository contains the implementations for - [Revisiting Deep Hyperspectral Feature Extraction Networks via Gradient Centralized Convolution](https://ieeexplore.ieee.org/document/9570352)

>📋  Abstract:
The hyperspectral images are composed of a variety of textures across the different bands which increase the spectral similarity and makes it difficult to predict the pixel-wise labels without inducing additional complexity at the feature level. To extract robust and discriminative features from the different regions of land-cover, the hyperspectral research community is still seeking such type of convolutions which can efficiently deal with fine-grained texture information during the feature extraction phase, which often overlook this aspect by vanilla convolution. To overcome the above shortcoming, this paper proposes a generalized gradient centralized 3D convolution (G2C-Conv3D) operation, which is a weighted combination between the vanilla and gradient centralized 3D convolutions (GC-Conv3D) to extract both the intensity level semantic information and gradient level information. Which can be easily plugged into the existing HSI feature extraction networks to boost the performance of accurate prediction for land-cover types. To validate the feasibility of the proposed G2C-Conv3D, we have considered the existing CNN3D, MS3DNet, ContextNet and SSRN feature extraction models and as well as CAE3D, VAE3D, and SAE3D autoencoder (AE) networks, respectively. All these networks are embedded with G2C-Conv3D convolution to implement both generalized gradient centralized feature extraction networks (G2C-FE) and generalized gradient centralized autoencoder networks (G2C-AE) for fine-grained spectral-spatial feature learning. In addition, G2C-Conv2D is also considered with few networks. The extensive experiments are conducted on four most widely used hyperspectral datasets i.e., IP, KSC, UH, and UP, respectively, and compared with nine methods. The results demonstrate that the proposed G2C-Conv3D can effectively enhanced the feature learning ability of the existing networks and both the qualitative and quantitative results show the superiority and effectiveness of the proposed G2C-Conv3D.

<img src="CDC.jpg"/>
                              


If you have questions or suggestions, please feel free to open an issue. Please cite as:

```
@article{roy2021revisiting,
  title={Revisiting Deep Hyperspectral Feature Extraction Networks via Gradient Centralized Convolution},
  author={Swalpa Kumar Roy, and Purbayan Kar, and Danfeng Hong, and Xin Wu, and Antonio Plaza, and Jocelyn Chanussot},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  year={2021},
  publisher={IEEE}
}
```

The dataset files need to be placed inside a folder in the root directory and the folder should have the same name as the dataset itself. For example - "Houston/houston.mat" where Houston is the folder name and houston.mat is the HSI data file. 

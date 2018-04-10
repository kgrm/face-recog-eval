# face-recog-eval

This is a model repository for the following article:

Grm, K., Štruc, V., Artiges, A., Caron, M., Ekenel, H. K. Strengths
and Weaknesses of Deep Learning Models for Face Recognition Against
Image Degradations. Published in: IET Biometrics, 2017.

The article has been published at the [IET digital library](http://digital-library.theiet.org/content/journals/10.1049/iet-bmt.2017.0083). An [arXiv copy](https://arxiv.org/abs/1710.01494) is also available.

We provide the pre-trained face recognition models for four common CNN architectures, namely,

* AlexNet
* GoogLeNet (InceptionV3)
* VGG-Face
* SqueezeNet

The models were trained on a subset of the VGG face dataset that contains approximately 1.8 million face images across 2622 identities.

Model definitions and weights are available [here](https://www.dropbox.com/s/nwkpiwrn35mgfem/face-recog-eval.zip?dl=0).

The following software versions were used and are recommended:

* Python 2.7
* Numpy 1.13
* h5py 2.7
* Theano 0.8
* Keras 1.2
* OpenCV 2.4

If you use our trained models, please cite the above paper as follows:

```
@article{grm2017strengths,
  title={Strengths and weaknesses of deep learning models for face recognition against image degradations},
  author={Grm, Klemen and {\v{S}}truc, Vitomir and Artiges, Anais and Caron, Matthieu and Ekenel, Haz{\i}m K},
  journal={IET Biometrics},
  volume={7},
  number={1},
  pages={81--89},
  year={2017},
  publisher={IET}
}
```

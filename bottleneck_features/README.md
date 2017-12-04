Multiple architectures can be used for transfer learning. The bottleneck features of each architecture can be downloaded from the following sources:

- [VGG-16](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) bottleneck features
- [VGG-19](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG19Data.npz) bottleneck features
- [ResNet-50](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogResnet50Data.npz) bottleneck features
- [Inception](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogInceptionV3Data.npz) bottleneck features
- [Xception](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogXceptionData.npz) bottleneck features

The files are encoded as such:

    Dog{network}Data.npz
    
where `{network}`, in the above filename, can be one of `VGG16`, `VGG19`, `Resnet50`, `InceptionV3`, or `Xception`. The bottleneck features need to be stored in this folder after they are downloaded.

The code for using the bottleneck features for all the pre-trained models from above is already available in the notebook (but commented in some cases).

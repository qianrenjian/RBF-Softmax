# Setting Up Data Paths

Expected datasets structure for ImageNet:

```
imagenet
|_ train
|  |_ n01440764
|  |_ ...
|  |_ n15075141
|_ val
|  |_ n01440764
|  |_ ...
|  |_ n15075141
|_ ...
```

Create a directory containing symlinks:

```
mkdir -p /path/RBF-Softmax/pycls/datasets/data
```

Symlink ImageNet:

```
ln -s /path/imagenet /path/RBF-Softmax/pycls/datasets/data/imagenet
```
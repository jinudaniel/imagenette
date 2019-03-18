# Imagenette

Imagenette is a subset of 10 easily classified classes from Imagenet 
(tench, English springer, cassette player, chain saw, church, French horn, garbage truck, gas pump, golf ball, parachute). More details
can be found at the [official page](https://github.com/fastai/imagenette).  

| Size  | Accuracy |
| ------------- | ------------- |
| 160px  | 89% |
| 320px |  |

This classifier is trained on a google cloud n1-highmem-8 instance with Nvidia P4 GPU.

## TODO
* Train for more epochs and see if the accuracy improves.
* Optimize the hyperparameters like learning rate, conv architecture etc.

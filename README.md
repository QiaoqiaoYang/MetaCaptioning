# Code for the TGRS2021 article 'Meta Captioning: A Meta Learning Based Remote Sensing Image Captioning Framework'.
---------------------------------------------
* Here I provide Pytorch implementations for remote sensing image captioning on UCM dataset.

* I was inspired to an extent by the nice repositories <br> <https://github.com/ruotianluo/self-critical.pytorch> <br>
I feel grateful to the authors for providing them.

## * Environment & Main Dependencies
>CentOS Linux release 7.2.1511 (Core)<br>
>python 3.6.11<br>
>torchvision 0.2.1<br>
>Pytorch 1.3.0

## * Usage
* Download hyperspectral data and add them to `./dataset`.<br>
* All the hyperparameters are in `./tflib/config.py`.<br>
Set them to what you want when running a code.<br>
* Run<br>
`python GAL.py -GPU 0` <br> 
to see GAL in the local mode on the Salinas dataset.

## * Citation


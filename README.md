# Code for the 'Meta Captioning'.
---------------------------------------------
* Here I provide Pytorch implementations for remote sensing image captioning on UCM dataset.

* I was inspired to an extent by the nice repositories <br> <https://github.com/ruotianluo/self-critical.pytorch> <br>
I am very grateful to the authors for providing them.

## * Environment & Main Dependencies
>CentOS Linux release 7.2.1511 (Core)<br>
>python 3.6.11<br>
>torchvision 0.2.1<br>
>Pytorch 1.3.0

## * Usage

>(1)Gain the meta features <br>
Specific steps are written in the paper, we provide well-tranined parameters value in ./data<br>
>(2)Representing remote sensing images <br>
python prepro_feats.py<br>
>(3)Transmitting the labels<br>
>python prepro_labels.py <br>
we provide corresponding files of UCM in ./data<br>
>(4)Training<br>
python train.py <br>
......<br>
>(5)Testing:<br>
python eval.py <br>
Specific configuration information will be forthcoming

## * Citation


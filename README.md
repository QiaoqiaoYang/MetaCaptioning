# Code for the 'Meta Captioning'.
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
coming soon
For traning:
(1)Gain the meta features 
Specific steps are written in the paper, we provide well-tranined parameters value in ./data
(2)Representing remote sensing images 
python prepro_feats.py
(3)Transmitting the labels
python prepro_labels.py 
we provide corresponding files of UCM in ./data
(4)Training
python train.py 
(5)Testing:
python eval.py 
......

## * Citation


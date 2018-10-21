# Kaggle TGS Salt Identification Challenge
*Using the fast.ai library to build pre-trained ResNet34 + U-net solution to the [Kaggle TGS Salt Identification Challenge](https://www.kaggle.com/c/tgs-salt-identification-challenge/overview) on kaggle.*

<img src="https://github.com/jamesdellinger/kaggle_tgs_salt_identification_challenge/blob/master/images/thumb76_76.png" height="140">

## My Competition Solution
* [Notebook](http://nbviewer.jupyter.org/github/jamesdellinger/kaggle_tgs_salt_identification_challenge/blob/master/kernel_tgs_salt_sub6_unet-ish_resnet34_(BEST).ipynb)

## Concepts
* U-net networks: https://arxiv.org/pdf/1505.04597.pdf
* Gradual unfreezing and discriminiative fine-tuning: https://arxiv.org/pdf/1801.06146.pdf
* One-cycle training with momentum: https://arxiv.org/pdf/1803.09820.pdf
* Lovasz hinge loss: https://arxiv.org/pdf/1705.08790.pdf
* Concurrent Spatial and Channel Squeeze & Excitation: https://arxiv.org/pdf/1803.02579.pdf
* Snapshot ensembling: https://arxiv.org/pdf/1704.00109.pdf

## Background
* I began this competition in late September, 2018, after going through all 14 lessons of fast.ai's [Practical Deep Learning For Coders, Part 1](http://course.fast.ai/) and [Cutting Edge Deep Learning For Coders, Part 2](http://course.fast.ai/part2.html) courses.
* The material presented in the [Carvana notebook](https://github.com/fastai/fastai/blob/master/courses/dl2/carvana-unet.ipynb) presented in [Lesson 14] of the course served as the foundation upon which I built my solution.

## Competition Summary
* Many untapped oil deposits beneath the earth's surface happen to lie close to salt deposits. In order to safely drill for oil in these areas, drilling companies need to know precisely where the salt deposits are positioned, so that they can avoid them. 
* The current method is for seismic images of the sediment under the earth's surface to be interpreted by trained experts, who draw the boundaries of salt deposits by hand.
* This is a time-consuming and potentially error-prone process. The goal of this competition was to see if kagglers could build salt-detection classifiers that could serve as tools to aid and augment the reviewers, whose painstaking work is currently all done by hand.

## Dependencies
* [requirements.txt](https://github.com/jamesdellinger/kaggle_tgs_salt_identification_challenge/blob/master/requirements.txt)

* [environment.yml](https://github.com/jamesdellinger/kaggle_tgs_salt_identification_challenge/blob/master/exploration.ipynb)
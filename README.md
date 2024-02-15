# ros2
Provides a quick and easy way to get up and running with a DeepRacer training environment using a cloud virtual machine or a local compter, such [AWS EC2 Accelerated Computing instances](https://aws.amazon.com/ec2/instance-types/?nc1=h_ls#Accelerated_Computing) or the Azure [N-Series Virtual Machines](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sizes-gpu).

DRfC runs on Ubuntu 20.04 or 22.04. GPU acceleration requires a NVIDIA GPU, preferrably with more than 8GB of VRAM.

## Introduction

DeepRacer-For-Cloud (DRfC) started as an extension of the work done by Alex (https://github.com/alexschultz/deepracer-for-dummies), which is again a wrapper around the amazing work done by Chris (https://github.com/crr0004/deepracer). With the introduction of the second generation Deepracer Console the repository has been split up. This repository contains the scripts needed to *run* the training, but depends on Docker Hub to provide pre-built docker images. All the under-the-hood building capabilities are in the [Deepracer Build](https://github.com/aws-deepracer-community/deepracer) repository.

## Main Features

DRfC supports a wide set of features to ensure that you can focus on creating the best model:
* User-friendly

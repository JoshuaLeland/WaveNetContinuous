# WaveNetContinuous
Modified version of WaveNet that uses continous values of -1, 1 instead of the probabilistic quantized distrubution. This is going to be used as part of our genre to genre translation project using CycleGANs.  The original version of WaveNet would not work with a cycleGAN because the argmax of a catagorical distrubution is not differentable.

The original code is here: https://github.com/NVIDIA/nv-wavenet/tree/master/pytorch

This was not a lot of work to convert, so if you are using this for anything please referance the original paper: https://arxiv.org/abs/1609.03499

The testing notebook is not complete.  I will be updating it as I continue with this project.

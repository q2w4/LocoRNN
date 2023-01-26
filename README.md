# Neural Wave Machines: Learning Spatiotemporally Structured Representations with Locally Coupled Oscillatory Recurrent Neural Networks

This repository contains all code necessary to reproduce the experiments in the paper. Additionally, we include video visualizations of the spatiotemporal dynamics for each dataset in the README below. 

## Hidden State Visualizations 

#### 2D NWM on Rotating MNIST

Before Training:

<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/before_training_rot_mnist.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/before_training_rot_mnist_phase.gif" width="100" height="100" />

After Training: 

<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/wave_s4main_pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/wave_s4main_phase.gif" width="100" height="100" />

Hidden state of same model but on different data samples:

<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/wave_s1_pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/wave_s1_phase.gif" width="100" height="100" /> 
<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/wave_s2_pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/wave_s2_phase.gif" width="100" height="100" />
<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/wave_s3_pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/wave_s3_phase.gif" width="100" height="100" />
<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/wave_s5_pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/wave_s5_phase.gif" width="100" height="100" />

Hidden state of 2D NWM with different random initalizations:

<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/randinit2_waves_pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/randinit2_waves_phase.gif" width="100" height="100" /> 
<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/randinit3_waves_pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/randinit3_waves_phase.gif" width="100" height="100" />
<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/randinit4_waves_pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_mnist/randinit4_waves_phase.gif" width="100" height="100" />

#### 2D NWM on Spring Task 
(Ground Truth, Forward Extrapolated Reconstruction, Hidden State, Phase)

<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_spring/gt.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_spring/recon.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_spring/pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_spring/phase.gif" width="100" height="100" /> 

#### (Baseline) Globally Coupled coRNN on Spring Task 
(Ground Truth, Forward Extrapolated Reconstruction, Hidden State, Phase)

<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/coRNN_Spring/gt.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/coRNN_Spring/recon.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/coRNN_Spring/pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/coRNN_Spring/phase.gif" width="100" height="100" /> 


#### 2D NWM on Pendulum Task
<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_pendulum/gt.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_pendulum/recon.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_pendulum/pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_pendulum/phase.gif" width="100" height="100" /> 

#### (Baselinne) Globally Coupled coRNN on Pendulum Task
<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/coRNN_pendulum/gt.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/coRNN_pendulum/recon.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/coRNN_pendulum/pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/coRNN_pendulum/phase.gif" width="100" height="100" /> 

#### 2D NWM on 2-Body Task
<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_2body/gt.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_2body/recon.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_2body/pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/NWM_2d_2body/phase.gif" width="100" height="100" /> 

#### (Baseline) Globally Coupled coRNN on 2-Body Task
<img src="https://github.com/q2w4/LocoRNN/blob/master/figures/coRNN_2body/gt.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/coRNN_2body/recon.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/coRNN_2body/pos.gif" width="100" height="100" /> <img src="https://github.com/q2w4/LocoRNN/blob/master/figures/coRNN_2body/phase.gif" width="100" height="100" /> 
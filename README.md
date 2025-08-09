We present sound examples from WaveGAN and our ICEEMDGAN models. Each sound file represents fifty examples of one second in length concatenated together, with a half second of silence after each example. All models are trained in the unsupervised setting and results here are a random sampling of fifty latent vectors.

Speech Commands Zero through Nine (SC09)
The SC09 dataset, a subset of the ([Speech Commands](https://research.googleblog.com/2017/08/launching-speech-commands-dataset.html)) dataset ([license](https://creativecommons.org/licenses/by/4.0/)), has many speakers and a ten word vocabulary. When trained on this dataset without label conditioning, our WaveGAN and SpecGAN models learn to generate coherent words. Results are arranged into numerical ordering by post-hoc labeling of random examples by the classifier discussed in the paper.

Real data


https://github.com/user-attachments/assets/512f7caf-4d34-4cf7-88a4-0d3b8a3f0de1

WaveGAN


https://github.com/user-attachments/assets/956e06ad-5bc7-410b-92b8-2da9466893a1

ICEEMDGAN

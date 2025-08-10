We present sound examples from WaveGAN and our ICEEMDGAN models. Each sound file represents fifty examples of one second in length concatenated together, with a half second of silence after each example. All models are trained in the unsupervised setting and results here are a random sampling of fifty latent vectors.

Speech Commands Zero through Nine (SC09)
The SC09 dataset, a subset of the ([Speech Commands](https://research.googleblog.com/2017/08/launching-speech-commands-dataset.html)) dataset ([license](https://creativecommons.org/licenses/by/4.0/)), has many speakers and a ten word vocabulary. When trained on this dataset without label conditioning, our WaveGAN and SpecGAN models learn to generate coherent words. Results are arranged into numerical ordering by post-hoc labeling of random examples by the classifier discussed in the paper.

Real data


https://github.com/user-attachments/assets/7edb10d7-4aa5-4385-90ce-274fc92887f9


WaveGAN


https://github.com/user-attachments/assets/97cf142a-f000-4634-955d-1400afa4d64f


EMDGAN


https://github.com/user-attachments/assets/5efcd7e2-6a60-435b-a916-13c44d95dc22


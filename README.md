<img src="terminal.svg" width="100%" alt="Terminal bio animation"/>


## Research

Broadly into computer vision and deep learning. Most of my work asks whether something assumed to be true actually holds up under scrutiny.

**[Spectral Mamba](https://github.com/Subkash2206/spectral-mamba-analysis)** · Does Mamba's scan mechanism introduce aliasing that hurts boundary segmentation? Audited VM-UNet against Swin and UNet on ISIC2018 (N=519). Hypothesis not supported, but the analysis uncovered a dual-stage spectral fingerprint in SSMs: high-frequency front-loading at Stage 1 that collapses by Stage 4. A previously reported AVR-BF1 correlation also turned out to be an intensity bias artifact once DC correction was applied.

**[Brain Tumor Segmentation · MIDL 2026](https://github.com/Subkash2206/aliasing-tumor-boundaries)** · Does BlurPool help 3D medical image segmentation? Tested on BraTS 2021 using SegResNet. Small performance drop and a counterintuitive shift consistency regression (98% to 91%). Null results need reporting too.

**[Spectral Aliasing in CNNs](https://github.com/Subkash2206/spectral-aliasing-cnns)** · Introduced AVR and SIS to quantify aliasing behavior in convolutional networks on STL-10. BlurPool reduces shift instability by ~39.8%, but networks appear to compensate by learning higher pre-blur aliasing. Preprint in progress.


## Contact

[subhashkashyap2206@gmail.com](mailto:subhashkashyap2206@gmail.com) · [github.com/Subkash2206](https://github.com/Subkash2206)

<sub>Into deep learning and computer vision.</sub>

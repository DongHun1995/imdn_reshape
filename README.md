# IMDN-4x model

This repository is based on Lightweight Image Super-Resolution with Information Multi-distillation Network (ACM MM 2019)

[[arXiv]](https://arxiv.org/pdf/1909.11856v1.pdf)
[[Poster]](https://github.com/Zheng222/IMDN/blob/master/images/acmmm19_poster.pdf)
[[ACM DL]](https://dl.acm.org/citation.cfm?id=3351084)


## Testing

setups
```bash
conda create -n imdn python=3.8
conda activate imdn
pip install pytorch opencv-python scikit-image pillow torchvision hdf5storage ninja lmdb requests timm einops
#if this code doesn't work you should downgrade version because this code was devloped in 2019
```

- Runing testing:

```bash
python main_test_imdn.py

```


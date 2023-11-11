---
title: "Pytorch implementation of HDMI denoising method"
date: "2021-05-19"
categories: 
  - "code"
---

I just released a pytorch implementation of the [HDMI denoising method](https://houdard.wp.imt.fr/2018/02/23/new-version-of-hdmi/) that can be used on GPU: [github.com/ahoudard/HDMI](https://github.com/ahoudard/HDMI)

This version allows to run the EM algorithm and the denoising in about half a minute!

```
python run_HDMI_denoising.py alley.png --stdv 0.1 --n_iter 40 --verbose --gpu
selected device: cuda
run EM algorithm...
denoise patches...
total runtime: 34s
PSNR: 29.8940dB
```

- ![](images/alley-1.png)
    
    clean image
    
- ![](images/alley_noisy.png)
    
    noisy image
    
- ![](images/alley_denoised-1.png)
    
    denoised image

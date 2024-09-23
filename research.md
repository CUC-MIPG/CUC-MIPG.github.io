---
layout: default
title: Current Projects
desc: Check out what we're working on
nav: Research
---

# MAG-Edit: Localized Image Editing in Complex Scenarios via Mask-Based Attention-Adjusted Guidance

Together with [Yuchao Gu](https://ycgu.site/) and [Mike Zheng Shou](https://sites.google.com/view/showlab), we develop MAG-Edit ：the first method specifically designed to address localized image editing in complex scenarios without training.Recent diffusion-based image editing approaches have exhibited impressive editing capabilities in images with simple compositions. However, localized editing in complex scenarios has not been well-studied in the literature, despite its growing real-world demands. Existing mask-based inpainting methods fall short of retaining the underlying structure within the edit region. Meanwhile, mask-free attention-based methods often exhibit editing leakage and misalignment in more complex compositions. In this work, we develop MAG-Edit, a training-free, inference-stage optimization method, which enables localized image editing in complex scenarios. In particular, MAG-Edit optimizes the noise latent feature in diffusion models by maximizing two mask-based cross-attention constraints of the edit token, which in turn gradually enhances the local alignment with the desired prompt. Extensive quantitative and qualitative experiments demonstrate the effectiveness of our method in achieving both text alignment and structure preservation for localized editing within complex scenarios.[[Paper]](https://arxiv.org/abs/2312.11396)[[Code]](https://github.com/HelenMao/MAG-Edit)[[Page]](https://mag-edit.github.io/)
<div class="row">
    <figure>
        <img src="/images/show/MAG/framework.png" class="img-responsive">
        <figcaption>
            High-level overview of the proposed MAG-Edit framework.
        </figcaption>
    </figure>
</div>

# Super Resolved Imaging with Adaptive Optics

<img width="1523" height="583" alt="aosr_teaser" src="https://github.com/user-attachments/assets/573dc486-5555-41ac-82d5-0aa187eb9c32" />

## Abstract

> Astronomical telescopes suffer from a tradeoff between field-of-view (FoV) and image resolution: increasing the FoV leads to an optical field that is under-sampled by the science camera. This work presents a novel computational imaging approach to overcome this tradeoff by leveraging the existing adaptive optics (AO) systems in modern ground-based telescopes. Our key idea is to use the AO system’s deformable mirror to apply a series of learned, precisely controlled distortions to the optical wavefront, producing a sequence of images that exhibit distinct, high-frequency, sub-pixel shifts. These images can then be jointly upsampled to yield the final super-resolved image. Crucially, we show this can be done while simultaneously maintaining the core AO operation—correcting for the unknown and rapidly changing wavefront distortions caused by Earth's atmosphere. To achieve this, we incorporate end-to-end optimization of both the induced mirror distortions and the upsampling algorithm, such that telescope-specific optics and temporal statistics of atmospheric wavefront distortions are accounted for. Our experimental results with a hardware prototype, as well as simulations, demonstrate significant SNR improvements of up to 12 dB over non-AO super-resolution baselines, using only existing telescope optics and no hardware modifications. Moreover, by using a precise bench-top replica of a complete telescope and AO system, we show that our methodology can be readily transferred to an operational telescope. 

## Links & Data

- 📃 **Paper** — Available on [arXiv](https://arxiv.org/abs/2508.04648)
- 🌐 **Project Website** — [https://www.cs.toronto.edu/~robin/aosr/](https://www.cs.toronto.edu/~robin/aosr/)

> [!NOTE]
> Code, data, and simulation scripts will be available soon

## Citing AOSR

```bibtex
@inproceedings{swanson2025super,
    title={Super Resolved Imaging with Adaptive Optics},
    author={Swanson, Robin and Lin, Esther Y. H. and Lamb, Masen and Sivanandam, Suresh and Kutulakos, Kiriakos N.},
    booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    year={2025},
}
```

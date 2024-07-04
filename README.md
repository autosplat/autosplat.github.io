# AutoSpalt: Constrained Gaussian Splatting for Autonomous Driving Scene Reconstruction

**Authors:** [Mustafa Khan](https://ca.linkedin.com/in/mustafarehanahmadkhan), [Hamidreza Fazlali](https://scholar.google.com/citations?hl=en&user=0fhlNwEAAAAJ&view_op=list_works&sortby=pubdate), [Dhruv Sharma](https://scholar.google.com/citations?hl=en&user=tJ-3yAkAAAAJ&view_op=list_works&sortby=pubdate), [Tongtong Cao](https://scholar.google.com/citations?hl=en&user=SkzzXSYAAAAJ&view_op=list_works&sortby=pubdate), [Dongfeng Bai](https://scholar.google.com/citations?hl=zh-CN&user=aubQLGYAAAAJ&view_op=list_works&sortby=pubdate), [Yuan Ren](https://scholar.google.com/citations?hl=en&user=P4Rp5uAAAAAJ&view_op=list_works&sortby=pubdate), [Bingbing Liu](https://scholar.google.com.sg/citations?hl=en&user=-rCulKwAAAAJ&view_op=list_works&sortby=pubdate)

Realistic scene reconstruction and view synthesis are essential for advancing autonomous driving systems by simulating safety-critical scenarios. 3D Gaussian Splatting excels in real-time rendering and static scene reconstructions but struggles with modeling driving scenarios due to complex backgrounds, dynamic objects, and sparse views. We propose AutoSplat, a framework employing Gaussian splatting to achieve highly realistic reconstructions of autonomous driving scenes. By imposing geometric constraints on Gaussians representing the road and sky regions, our method enables multi-view consistent simulation of challenging scenarios including lane changes. Leveraging 3D templates, we introduce a reflected Gaussian consistency constraint to supervise both the visible and unseen side of foreground objects. Moreover, to model the dynamic appearance of foreground objects, we estimate residual spherical harmonics for each foreground Gaussian. Extensive experiments on Pandaset and KITTI demonstrate that AutoSplat outperforms state-of-the-art methods in scene reconstruction and novel view synthesis across diverse driving scenarios.

## BibTeX
Please cite our work as:
```
@misc{khan2024autosplatconstrainedgaussiansplatting,
      title={AutoSplat: Constrained Gaussian Splatting for Autonomous Driving Scene Reconstruction}, 
      author={Mustafa Khan and Hamidreza Fazlali and Dhruv Sharma and Tongtong Cao and Dongfeng Bai and Yuan Ren and Bingbing Liu},
      year={2024},
      eprint={2407.02598},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2407.02598}, 
}
```

## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

# UnsupervisedNet

[**Wenhui Zhou**](https://faculty.hdu.edu.cn/jsjxy/zwh_en/main.htm), Enci Zhou, Gaoming Liu, Lili Lin, Andrew Lumsdaine. [**Unsupervised Monocular Depth Estimation from Light Field Image**](https://doi.org/10.1109/TIP.2019.2944343), IEEE Transactions on Image Processing, 2020, 29: 1606-1617. 

- download the [model](https://drive.google.com/file/d/1tAT0i4Wpa5zaym4Ath2BAiGkxHAcx2sD/view?usp=sharing) and [evaluation_toolkit](https://drive.google.com/file/d/1Q69Bb32RAiV25ILDgIvZSydP1BMQYUVY/view?usp=sharing)
- unzip the model and evaluation_toolkit in root directory
  ```
    ./UnsupervisedNet
    ├── 4dlffilenames_val7x7star.txt
    ├── average_gradients.py
    ├── bilinear_samplerzb.py
    ├── dataloader_lf7x7star_zec.py
    ├── evalfunctions7x7.py
    ├── eval_tools.py
    ├── evaluate.py
    ├── evaluation_toolkit
    ├── model
    ├── monodepth_main_getresultLF7x7Star.py
    ├── monodepth_model_LF7x7Star.py
    ├── optical_flow_warp_fwd.py
    ├── REMADE.md
    └── result
    ```
- run "python3 monodepth_main_getresultLF7x7Star.py" to test model

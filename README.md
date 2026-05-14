# MM01LLCM-Text

The **MM01LLCM-Text** dataset is designed for the **Text-Visible/Infrared Person Retrieval** task, enabling research on person retrieval across visible and infrared modalities using text descriptions. This dataset is constructed based on the [SYSU-MM01 dataset](https://github.com/wuancong/SYSU-MM01) and the [LLCM dataset](https://github.com/ZYK100/LLCM).

## Download Instructions

To use the **MM01LLCM-Text** dataset, please follow the steps below:

1. **Download the SYSU-MM01 dataset** from [here](https://github.com/wuancong/SYSU-MM01).
2. **Download the LLCM dataset** from [here](https://github.com/ZYK100/LLCM).
3. **Download [captions.json](captions.json)** from this repository.
4. Place the SYSU-MM01 dataset, the LLCM dataset, and `captions.json` under the same root directory.

Your folder structure should look like this:

```text
|-- <root> /
|  |-- SYSU-MM01 /
|  |-- LLCM /
|  |-- captions.json
```

## License and Copyright

The images in the **MM01LLCM-Text** dataset are sourced from the original SYSU-MM01 and LLCM datasets. When using this dataset, users must comply with the copyright terms and usage licenses of the original SYSU-MM01 and LLCM datasets.

For the text descriptions, you are permitted to use them for academic research. Any use of the text annotations requires proper attribution, including citation of the source in related publications or public releases.

## Citation
```text
@ARTICLE{11516553,
  author={Li, Chenglong and Xu, Ziheng and Deng, Yifei and Zheng, Aihua and Tang, Jin},
  journal={IEEE Transactions on Image Processing}, 
  title={Text-Visible/Infrared Person Retrieval: Attribute-Guided Feature Decoupling and Collaborative Alignment and A Unified Benchmark}, 
  year={2026},
  doi={10.1109/TIP.2026.3691012}}
```

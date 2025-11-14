# AquaClarity: Vision Transformer Enhances Underwater Image via Nonlinear Feature Fusion and Color Fidelity Improvement

[Xuhang Chen](https://cxh.netlify.app/), Zimeng Li📮, Xiujun Zhang, Yingtie Lei, Yihang Dong, Xiaofeng Zhang, [Chi-Man Pun](https://www.cis.um.edu.mo/~cmpun/) ( 📮 Corresponding author)

**Huizhou University, Shenzhen Polytechnic University, University of Macau, SIAT CAS, Shanghai Jiao Tong University**

IEEE Transactions on Consumer Electronics

# 🔮 Dataset

The dataset is available at [Kaggle](https://www.kaggle.com/datasets/xuhangc/underwaterbenchmarkdataset).

# ⚙️ Usage

## Training

You may download the dataset first, and then specify TRAIN_DIR, VAL_DIR and SAVE_DIR in the section TRAINING in `config.yml`.

For single GPU training:

```bash
python train.py
```

For multiple GPUs training:

```bash
accelerate config
accelerate launch train.py
```

If you have difficulties with the usage of `accelerate`, please refer to [Accelerate](https://github.com/huggingface/accelerate).

## Inference

```bash
python test.py
```

# 💗 Acknowledgement

This work was supported in part by Shenzhen Medical Research Fund (Grant No. A2503006), in part by the National Natural Science Foundation of China (Grant No. 62501412 and 62272313), in part by Shenzhen Polytechnic University Research Fund (Grant No. 6025310023K), in part by the Science and Technology Development Fund, Macau SAR, under Grant 0193/2023/RIA3 and 0079/2025/AFJ and and in part by Guangdong Basic and Applied Basic Research Foundation (Grant No. 2024A1515140010).

# 🛎 Citation

If you find our work helpful for your research, please cite:
```bib
@ARTICLE{11242133,
  author={Chen, Xuhang and Li, Zimeng and Zhang, Xiujun and Lei, Yingtie and Dong, Yihang and Zhang, Xiaofeng and Pun, Chi-Man},
  journal={IEEE Transactions on Consumer Electronics}, 
  title={AquaClarity: Vision Transformer Enhances Underwater Image via Nonlinear Feature Fusion and Color Fidelity Improvement}, 
  year={2025},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TCE.2025.3631911}
}
```

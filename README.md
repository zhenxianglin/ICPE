# Intra-Class Probabilistic Embeddings for Uncertainty Estimation in Vision-Language Models

<!-- [![Paper](https://img.shields.io/badge/Paper-PDF-red)](path_to_your_paper_link_if_available)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) -->


This is the official code for WACV 2026 paper [Intra-Class Probabilistic Embeddings for Uncertainty Estimation in Vision-Language Models](https://www.arxiv.org/abs/2511.22019)


![Method Overview](./src/image.jpg)

If you use this work, please cite:

```
@article{lin2025intra,
  title={Intra-Class Probabilistic Embeddings for Uncertainty Estimation in Vision-Language Models},
  author={Lin, Zhenxiang and Haghighat, Maryam and Browne, Will and Miller, Dimity},
  journal={arXiv preprint arXiv:2511.22019},
  year={2025}
}
```

<!-- **The code will be released soon.** -->

# Environment and Installation
Python 3.12.9 \
CUDA 12.6 \
PyTorch 2.7.0 \
torchvision 0.22.0 \
scikit-learn 1.6.1 \
scipy 1.15.2 \
[clip](https://github.com/openai/CLIP.git)

```bash
conda create -n icpe python=3.12.9 -y
conda activate icpe
pip install torch==2.7.0 torchvision==0.22.0 --index-url https://download.pytorch.org/whl/cu126
pip install scikit-learn==1.6.1 scipy==1.15.2
pip install ftfy regex tqdm
pip install git+https://github.com/openai/CLIP.git
pip install ipykernel
```


**Contact**

If you have any questions or comments, please contact [Zhenxiang Lin](mailito:z25.lin@qut.edu.au).


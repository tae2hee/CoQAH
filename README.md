# CoQAH
This repository is the implementation of [Generalizing Visual Question Answering from Synthetic to Human-Written Questions via a Chain of QA with a Large Language Model](https://arxiv.org/abs/2401.06400)

# Implementation for CLEVR
1. Clone [MDETR](https://github.com/ashkamath/mdetr) and follow instructions to setup environment.
2. Copy ipynb files in the mdetr folder of this repo to the cloned mdetr folder.
3. Download mdetr checkpoint trained on CLEVR from here [clevr_checkpoint.pth](https://zenodo.org/record/4721981/files/clevr_checkpoint.pth?download=1) and place it into the mdetr folder. Information about the checkpoint is available [here](https://github.com/ashkamath/mdetr/blob/main/.github/clevr.md#clevr)
4. Download [CLEVR-Human dataset (json files)](https://cs.stanford.edu/people/jcjohns/iep/) and [correspoing images](https://cs.stanford.edu/people/jcjohns/clevr/). Note that you need to configure the path to the dataset in the code to match your setup.



# Implementation for Chest X-rays
1. Clone [OFA](https://github.com/OFA-Sys/OFA) and follow instructions to setup environment.
2. Train finetune OFA model with [MIMIC-DIFF-VQA dataset](https://physionet.org/content/medical-diff-vqa/1.0.0/)
3. Copy ipynb files in the ofa folder of this repo to the cloned OFA folder.
4. Download PLEURAL checkpoint trained on MIMIC-DIFF-VQA from here []() and place it into the mdetr folder.
5. Download [VQA-RAD](https://osf.io/89kps/) and [SLAKE](https://www.med-vqa.com/slake/). Note that you need to configure the path to the dataset in the code to match your setup.

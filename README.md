# Reproducibility Study of: Dynamic Routing Tranformer Network for Multimodal Sarcasm Detection
Research study for course CS421: Natural Language Processing @ [UIC](https://www.uic.edu/).

The paper analyzed can be found [here](https://aclanthology.org/2023.acl-long.139), and its original repo [here](https://github.com/TIAN-viola/DynRT).

Study performed by:
 + [Eleonora Quaranta](https://github.com/elequaranta/)
 + [Infantino Andrea](https://github.com/InfantinoAndrea00)


## Setup

In order to reproduce the study that we have performed, follow these steps:
1. Create a subfolder of `source` called `dataset_image`.
2. Download the image data from [here](https://github.com/headacheboy/data-of-multimodal-sarcasm-detection).
3. Put all the installed images in the folder just created (i.e. in `source/dataset_image/`).
4. Into `run.ipynb` change the cell just under the voice **Preprocessing** with the path where you have stored the repo and, **if you are not using Gogle Colab** delete or comment the first cell.
5. Run all cells of file `run.ipynb`.

## Acknowledgements
Thanks for the original repo from https://github.com/TIAN-viola/DynRT

Thanks for the dataset from https://github.com/headacheboy/data-of-multimodal-sarcasm-detection

Thanks for the RoBERTa model from https://huggingface.co/roberta-base/

Thanks for the TRAR from https://github.com/rentainhe/TRAR-VQA
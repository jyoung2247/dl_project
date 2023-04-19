# dl_project

Citation for CleanRL:

@article{huang2022cleanrl,
  author  = {Shengyi Huang and Rousslan Fernand Julien Dossa and Chang Ye and Jeff Braga and Dipam Chakraborty and Kinal Mehta and João G.M. Araújo},
  title   = {CleanRL: High-quality Single-file Implementations of Deep Reinforcement Learning Algorithms},
  journal = {Journal of Machine Learning Research},
  year    = {2022},
  volume  = {23},
  number  = {274},
  pages   = {1--18},
  url     = {http://jmlr.org/papers/v23/21-1342.html}
}

Conda environment setup:

conda create -n dl_project python=3.9

conda activate dl_project

cd dl_project

pip install -r requirements/requirements.txt

pip install -r requirements/requirements-atari.txt

*If using a newer GPU (30 or 40 series):*

pip install "torch==1.12.1" --upgrade --extra-index-url https://download.pytorch.org/whl/cu113


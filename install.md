# Install
conda create -n diffusion python=3.10
conda activate diffusion
pip install -e .

# Develop
git clone repo without license or .gitignore
nbdev_new
nbdev_install_hooks

nbdev_export
pip install -e .

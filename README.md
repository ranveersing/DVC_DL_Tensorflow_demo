### DVC - DL - TF - AIOPS demo

### commands -
### create a new env
'''bash
conda create --prefix ./env python=3.7 -y
'''bash

### activate new env
source activate ./env
### init DVC
'''bash
git init
dvc init
'''bash

### create empty files -
'''bash
mkdir -p src/utils config
touch src/__init__.py src/utils/__init__.py param.yaml dvc.yaml config/config.yaml src/stage_01_load_save.py src/utils/all_utils.py setup.py .gitignore
'''bash

install src
pip install -e .
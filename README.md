# DVC AIOPS demo

## command -

### create a new env

```bash
conda create --prefix ./env python=3.8 -y
```

### activate new env 
```bash
source activate ./env
```
```bash
mkdir -p src/utils config
touch src/__init__.py src/utils/__init__.py param.yaml dvc.yaml config/config.yaml src/stage_01_load_save.py src/utils/all_utils.py setup.py .gitignore
```
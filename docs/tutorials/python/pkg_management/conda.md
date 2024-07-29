# CONDA 虚拟环境管理


## 10. 自动创建环境

```bash
conda create --prefix ./venv python==3.10.12
conda activate ./venv
```

```bash
pip install torch torchaudio funasr modelscope
conda install ffmpeg
```

导出

```bash
conda env export --prefix ./venv > environment.yml
```

安装:

```bash
conda env create --prefix ./venv --file environment.yml
conda activate .venv
```


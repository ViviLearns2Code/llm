# playground

## fun with nvidia
https://developer.nvidia.com/cuda-12-2-0-download-archive?target_os=Linux&target_arch=x86_64&Distribution=Ubuntu&target_version=20.04&target_type=deb_local

```bash
nvidia-smi
/usr/local/cuda/bin/nvcc --version
```

## dependencies
```bash
sudo apt install python3.8-venv
python3 -m venv ./venv
source ./venv/bin/activate
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

playground repo for data science related stuff

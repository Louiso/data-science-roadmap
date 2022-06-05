# Hola papi

# instalar conda

https://www.anaconda.com/products/distribution

https://phoenixnap.com/kb/how-to-install-anaconda-ubuntu-18-04-or-20-04

si da error: 

ejecutar esos comandos

```
  sudo apt update
  sudo apt upgrade
  sudo apt install -y python3-dev curl git
  curl -O https://bootstrap.pypa.io/get-pip.py
  python3 get-pip.py
  python3 -m pip install git+https://github.com/pypa/setuptools
  python3 get-pip.py
  python3 -m pip -V
```

creando env: 

conda create --name datascience_env
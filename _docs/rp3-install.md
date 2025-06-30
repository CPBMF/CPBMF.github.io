---
title: RP3 Instalação
nav_order: 2
parent: CPBMF
layout: default
---

[Github](https://github.com/Eduardo-vsouza/rp3)

[Documentação RP3](https://rp3-docs.readthedocs.io/en/latest/index.html)

## Instalando Anaconda e Bioconda

```bash
# Baixar o instalador do Anaconda
wget https://repo.anaconda.com/archive/Anaconda3-2024.02-1-Linux-x86_64.sh

# Instalar Anaconda de forma silenciosa no diretório atual
bash Anaconda3-2024.02-1-Linux-x86_64.sh -b -p "$PWD/anaconda3"

# Adicionar Anaconda ao PATH temporariamente
export PATH="$PWD/anaconda3/bin:$PATH"
source ~/.bashrc

# Verificar a instalação do Conda
conda --version

# Adicionar os canais necessários
conda config --add channels defaults
conda config --add channels bioconda
conda config --add channels conda-forge

# (Opcional) Instalar o mamba para acelerar a criação do ambiente
conda install mamba -n base -c conda-forge

# Criar o ambiente Conda com Python 3.10
mamba create --name bio-env python=3.10.0

# Ativar suporte ao shell
eval "$(mamba shell hook --shell bash)"
mamba activate bio-env
```
## Inicializando o ambiente Conda

``` bash

mamba init
mamba activate bio-env
```


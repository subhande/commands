# coomands

## WSL commands

```
wsl -l | wsl --list
wsl -l -v
wsl --shutdown
wsl --version
wsl --list --all
wsl --list --running

wsl --unregister <DistributionName>


```


# Anaconda commands

```
conda info --envs
conda env list


conda env create -f environment.yml
conda create --name envname
conda create --name envname python=3.8 --no-default-packages


conda env export > environment_droplet.yml
conda remove --name envname --all

source activate envname

```

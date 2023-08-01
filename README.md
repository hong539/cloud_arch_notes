# cloud_arch_notes
This is a project for me to collect the cloud system architecture and take some notes to extend more good enough system.

## prerequisites

* Python == 3.10.12
* [pyenv+poetry](https://github.com/hong539/setup_dev_environment/blob/main/programing_languages/python/python.md)
* [diagrams](https://github.com/mingrammer/diagrams)
* [Graphviz](https://gitlab.com/graphviz/graphviz)


## setting up

```shell
sudo pacman -Sy
sudo pacman -S graphviz
pyenv local 3.10.12
poetry new architectures
poetry shell
poetry add diagrams
```
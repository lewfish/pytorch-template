# pytorch-template

A [cookiecutter](https://cookiecutter.readthedocs.io/) template for starting a Docker-based PyTorch project. Assumming `cookiecutter` has been installed, you can run:

```
$ cookiecutter pytorch-template
project [my_project]:
caps_project [MY_PROJECT]:
dashed_project [my-project]:
author [Firstname Lastname]:
year [2020]:

$ tree my-project/
my-project/
├── Dockerfile
├── LICENSE
├── README.md
├── docker
│   ├── build
│   ├── ecr_publish
│   └── run
└── my_project
    └── __init__.py

2 directories, 7 files
```

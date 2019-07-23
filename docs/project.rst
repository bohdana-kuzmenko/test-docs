Dlab Project Structure
================================
Self-service, Fail-safe Exploratory Environment for Collaborative Data Science Workflow

Folder Structure Conventions

Folder structure options and naming conventions for software projects


|  ├── dlab_core               # * dlab_core package source files
|  │ ├── domain                # dlab_core package domain implementation
|  │ ├── infrastructure        # dlab_core package infrastructure implementation
|  │ ├── __init__.py           # define bound to names in the dlab_core package namespace
|  │ ├── __version__.py        # define version of current distributive
|  │ └── setup.py              # helper for setuptools
|  ├── providers               # * dlab_core infrastructure providers
|  │ ├── dlab_aws              # dlab_core package represent AWS cloud infrastructure managers
|  │ ├── dlab_azure            # dlab_azure package represent Azure cloud infrastructure managers
|  │ ├── dlab_gcp              # dlab_gcp package represent GCP cloud infrastructure managers
|  │ └── ...                   # ...
|  ├── tests                   # Unit tests
|  ├── LICENSE
|  ├── README.md
|  ├── requirements.txt        # lists of packages to install for dlab_core production environment
|  ├── requirements-dev.txt    # lists of packages to install for dlab_core development environment
|  ├── setup.py                # describe dlab_core module distribution to the Distutils
|  └── tox.ini                 # automate and standardize project testing in Python

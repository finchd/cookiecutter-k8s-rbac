cookiecutter-k8s-rbac
=====================

[![Build Status](https://travis-ci.com/finchd/cookiecutter-k8s-rbac.svg?branch=master)](https://travis-ci.com/finchd/cookiecutter-k8s-rbac)

*IMPORTANT* For generic modification, use the CNCF templating engine [Kustomize](https://github.com/kubernetes-sigs/kustomize)

[Cookiecutter](https://github.com/audreyr/cookiecutter ) template for Kubernetes RBAC Users/Groups/ServiceAccounts, Roles/ClusterRoles, etc

Table of Contents
-----------------

<!--ts-->
   * [cookiecutter-k8s-rbac](#cookiecutter-k8s-rbac)
      * [Table of Contents](#table-of-contents)
      * [Requirements](#requirements)
      * [Usage](#usage)
      * [License](#license)

<!-- Added by: finchd, at: 2018-11-02T20:49-07:00 -->

<!--te-->

Requirements
------------
Install `cookiecutter` command line: `pip install cookiecutter`    

Usage
-----
Generate a new Cookiecutter template layout: `cookiecutter gh:finchd/cookiecutter-k8s-rbac`

Development
-----------

This repository works like a standard Python project, plus the kubeyaml linting (yamllint):

1.  Clone this repository
2.  Create a virtual environment: `virtualenv .venv`
3.  Install the prerequisites: `pip install -r requirements.txt`
4.  Run the cookiecutter tests: `pytest -v`

Now that your local environment works, create/modify kubeyaml or hooks, checking them with the yamllint and pytest.
Don't forget to send a pull-request!

License
-------
This project is licensed under the terms of the [MIT License](/LICENSE)

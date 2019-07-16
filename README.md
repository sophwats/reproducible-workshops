# Reproducible workshop materials

This repository contains the materials and resources you need to create a reproducible workshop.

To get started with your own reproducible workshop, clone this repo and make sure your put all the required resources into your own copy.

The repository contains the following contents: 

* a [`doc`](./doc) folder, containing two files:
    1. [`for-presenters.md`](./doc/for-presenters.md) should contain information to aid the presenter of the workshop - from background material adding context, to more general information on the structure and flow of the workshop, detailed information about the workshop content and any other suggestions for the presenter. 
    2. [`abstract.md`](./doc/abstract.md) should contain the workshop abstract.

* a [`deploy`](./deploy) folder, containing: 
    1. [`deploy.md`](./deploy/deploy.md) gives clear instructions on how to deploy the workshop both within and outside of RHPDS.
    2. a [`templates`](./deploy/templates) folder, containing any OpenShift templates required to deploy the workshop, as well as any Ansible roles and playbooks.

* a [`slides`](./slides) folder conaining:
    1. [`rendered`](./rendered) which should contain a [slides.pdf](./rendered/slides.pdf) file of the slides, as well as any rendered videos which are to be shown in the workshop
    2. [`source`](./source) containing the source for the slides, either as a [powerpoint](./source/slides.pptx), google doc or keynote file.      

* a [`README.md`](.README.md) file, containing basic, high-level information about the lab. It should contain the lab title, abstract, keywords, intended workshop length(s) and any other relevant information. 

* a [`workshop.yaml`](./workshop.yaml) file, holding the following machine readable metadata:
    - name
    - authors
    - workshop duration
    - source repo
    - keywords

* a [`source`](./source) folder, containing:
    1. any code or Jupyter notebooks required to give the workshop
    2. data needed for the workshop
    3. a [`README.md`](./source/README.md) file, explaining all of the contents of the [`source`](./source) folder. 




# Reproducible workshop materials

This repository contains the materials and resources you need to create a reproducible workshop.

To get started with your own reproducible workshop, clone this repo and make sure your put all the required resorces into your own clone.

Your workshop repository should contain:
* a `README.md` file, containing basic, high-level information about the lab. It should contain the lab title, abstract, keywords, intended workshop length(s) and any other relevant information. 
* a `source` folder, containing any Jupyter notebooks or other source material
* `images`: metadata and source to create necessary images, if these are hosted or developed with the workshop
* `sildes`: either in the form of a gdocs link, keynote presentation file, powerpoint presentation or html, in addition to a pdf and a rendered video of any demos needed for the presentation 
* a `workshop.yaml` file, holding the following machine readable metadata:
    - name
    - authors
    - workshop duration
    - source repo
    - keywords
* a `presenters.txt` file to guide the workshop presenter, including:
    - any relevant background content 
    - suggestions for presenters
    - an abstract, suitible for resubmission of the workshop
    - speakers notes (unless included in the slides)
    - notes on modularity of the workshop (optional)
    - notes on ways to extend the length of the material (optional)
* a `deploy.md` file, containing documentation on how to deploy the lab. The file must contain:
    - a RHPDS link
    - instructions to deploy the workshop on RHDPS (in a single command)
    - instructions to deploy the workshop outside of RHPDS (in a single command)
* `templates` 
    - for all OpenShift templates necessary to deploy the workshop _and/or_
    - for all Ansible roles and playbooks necessary to deploy the workshop
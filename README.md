# Reproducible workshop materials

This repository contains materials needed to create a reproducible workshop, as well as guidance on how to make sure your workshop is being its best self. 

The workshop repository should contain:

    - a `README.md` file, containing basic, high-level information about the lab. It should contain the lab title, abstract, keywords, intended workshop length(s) and any other relevant information. 

    - a `source` folder, containing any Jupyter notebooks or other source material

    - `images`: metadata and source to create necessary images, if these are hosted or developed with the workshop

    - `sildes`: either in the form of a gdocs link, keynote presentation file, powerpoint presentation or html, in addition to a pdf and a rendered video of any demos needed for the presentation 

    - a `workshop.yaml` file, holding the following machine readable metadata:
         - name
         - authors
         - intended length
         - source repo
         - source branch
         - keywords

    - a `presenters.txt` file to guide the workshop presenter, including:
        - any relevant background content 
        - suggestions for presenters
        - an abstract, suitible for resubmission of the workshop
        - speakers notes (unless included in the slides)
        - notes on modularity of the workshop (optional)
        - notes on ways to extend the length of the material (optional)
        
    
## Deployment details
    The following content is required to guide the deployment of the workshop"
    - a `deploy.md` file, containing documentation on how to deploy the lab. The file must contain:
        - a RHPDS link
        - instructions to deploy the workshop on RHDPS
        - instructions to deploy the workshop outside of RHPDS
        (These _should_ be in the form of a single command.)
    - `templates` 
        - for all OpenShift templates necessary to deploy the workshop _and/or_
        - for all Ansible roles and playbooks necessary to deploy the workshop



rendered -- video and pdf but at least pdf
deploy
deploy.md -- documentation on how to deploy the lab
RHPDS link (must)
instructions to deploy on RHPDS (must)
instructions to deploy outside RHPDS (must)
SHOULD be a single command
templates -- OpenShift templates necessary to deploy (optional, but either this or ansible is necessary)
ansible -- Ansible roles and playbooks necessary to deploy (optional, but either this or templates is necessary)



# This is a big header
## this is a slightly smaller one

This is _way_ emphatic

This is **way, way** emphatic

This is `nerd speak`

> This is a blockquote

This is a link to [your favorite website](https://cats.io)
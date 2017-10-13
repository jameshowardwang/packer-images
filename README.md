# packer-images

Repository for Biohub packer images


## Workflow

If you're having trouble with any of these steps, ask in #eng-support

0. check out the repo
0. create a branch
0. copy ubuntu-example.json
0. change "ami_name" and "ami_description" to something descriptive
0. update the provisioner, build, run your instance, repeat until you're satisfied
0. push your branch and send a pull request


## Why this repo?

If you put your templates in this repo, the data-science and/CZI eng teams can help to do things like make updates, enforce best practices, etc.
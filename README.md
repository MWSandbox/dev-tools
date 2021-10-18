# Dev Tools <!-- omit in toc -->

This repository contains some useful scripts and configurations to setup the development environment.

1. [Git Tools](#git-tools)
   1. [Setup Pre-Commit Terraform hooks](#setup-pre-commit-terraform-hooks)

# Git Tools

## Setup Pre-Commit Terraform hooks
Can be used to install a pre-commit hook for https://github.com/antonbabenko/pre-commit-terraform.
Instructions:
1. Pull or build the image first
2. Adjust the readonly properties at the top of the script as needed
3. Run `bash setup-pre-commit-tf-docker-hook.sh`
4. Add a `.pre-commit-config.yaml` to your project

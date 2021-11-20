# FastAPI Ansible role [![Ansible Lint](https://github.com/namelivia/ansible-fastapi/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/namelivia/ansible-fastapi/actions/workflows/ansible-lint.yml)

This Ansible role contains some common tasks I use to deploy containerized FastAPI applications.

## Included tasks
 - `upgrade-alembic` Run alembic update to update the database schema to the latest version.

## Required variables

 - `application_name` Application name to run the commands on.

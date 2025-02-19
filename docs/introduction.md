# Ansible Development Tools (ADT)

## Introduction

Ansible Development Tools or ADT for short, aims to streamline the setup and usage of several tools needed in order to create [Ansible] content.
When it comes to creating automation content using Ansible, there are several packages available that can help users in different parts of the content creating journey. From bootstrapping new projects, all the way to ensuring content follows best practices and verifying it behaves as intended via well established test frameworks.

## Key Features

- All-in-One Ansible Toolkit: ADT combines critical Ansible development packages into a unified Python package.

- Simplified Ansible Automation: ADT focuses on crafting your automation scenarios and workflows with speed by reducing boilerplate code without
  dealing with the intricacies of managing and integrating different Ansible libraries.

For those looking for an IDE based experience, we also recommend you get familiar with the [Ansible extension for VSCode](https://marketplace.visualstudio.com/items?itemName=redhat.ansible).

## Included Packages

The curated list of tools installed as part of the Ansible Development Tools includes:

- [ansible-core](https://github.com/ansible/ansible): Ansible is a radically simple IT automation platform that makes your applications and systems easier to deploy and maintain. Automate everything from code deployment to network configuration to cloud management, in a language that approaches plain English, using SSH, with no agents to install on remote systems.
- [ansible-builder](https://github.com/ansible/ansible-builder): Ansible Builder automates the process of building execution environments using the schemas and tooling defined in various Ansible Collections and by the user.
- [ansible-lint](https://github.com/ansible/ansible-lint): Checks playbooks for practices and behavior that could potentially be improved.
- [ansible-navigator](https://github.com/ansible/ansible-navigator) A text-based user interface (TUI) for Ansible.
- [ansible-sign](https://github.com/ansible/ansible-sign): Utility for signing and verifying Ansible project directory contents.
- [molecule](https://github.com/ansible/molecule): Molecule aids in the development and testing of Ansible content: collections, playbooks and roles
- [pytest-ansible](https://github.com/ansible/pytest-ansible): A pytest plugin that enables the use of ansible in tests, enables the use of pytest as a collection unit test runner, and exposes molecule scenarios using a pytest fixture.
- [tox-ansible](https://github.com/ansible/tox-ansible): The tox-ansible plugin dynamically creates a full matrix of python interpreter and ansible-core version environments for running integration, sanity, and unit for an ansible collection both locally and in a Github action. tox virtual environments are leveraged for collection building, collection installation, dependency installation, and testing.

## Getting started

To get started, please follow the [installation](installation.md) steps to get ADT setup and jump into [Getting Started](getting_started.md) guide for details.

## Community

Questions, feedback, or contributions? Join the Ansible community on [Matrix](https://matrix.to/#/#devtools:ansible.com) or [open an issue](https://github.com/ansible/ansible-dev-tools/issues/new). We're dedicated to supporting your Ansible automation journey! For more details on how to interact with our community, please visit https://docs.ansible.com/ansible/latest/community/communication.html.

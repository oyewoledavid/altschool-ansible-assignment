# Altschool Ansible Assignment

This repository contains the Ansible assignment for Altschool. The purpose of this assignment is to demonstrate the ability to automate IT infrastructure using Ansible.
In this project I used ansible to install git and apache web server on two servers, ubuntu and centos. I also clone and hosted a web page on the two servers, i explore the use of roles in this project

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction
Ansible is an open-source automation tool used for configuration management, application deployment, and task automation. This assignment showcases various Ansible playbooks and roles to manage and configure servers.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Ansible installed on your local machine
- Access to the servers you want to manage
- Basic knowledge of Ansible and YAML

## Installation
To install Ansible, follow these steps:

1. Update your package manager:
    ```sh
    sudo apt update
    ```

2. Install Ansible:
    ```sh
    sudo apt install ansible
    ```

## Usage
To use the playbooks in this repository, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/oyewoledavid/altschool-ansible-assignment.git
    cd altschool-ansible-assignment
    ```

2. Run a playbook:
    ```sh
    ansible-playbook playbook.yml
    ```

## Contributing
Contributions are welcome! Please fork this repository and create a pull request with your changes.


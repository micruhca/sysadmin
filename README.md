# My SysAdmin Project
# DevOps практика с Terraform и Ansible

Решение задания по настройке инфраструктуры с помощью Terraform и Ansible.

## Структура проекта

- `terraform/` - конфигурация для развертывания 3 ВМ в Yandex Cloud
- `ansible/` - playbook и роли для настройки машин
Структура: 

├── ansible
│   ├── ansible.cfg
│   ├── inventory.ini
│   ├── inventory.yaml
│   ├── playbook.yml
│   ├── roles
│   │   ├── base_setup
│   │   │   └── tasks
│   │   │       └── main.yml
│   │   ├── nginx_proxy
│   │   │   ├── handlers
│   │   │   │   └── main.yml
│   │   │   └── tasks
│   │   │       └── main.yml
│   │   └── nginx_web
│   │       └── tasks
│   │           └── main.yml
│   └── templates
│       ├── index.html.j2
│       ├── nginx.conf.j2
│       └── proxy.conf.j2
├── terraform_yandex
    ├── cloud_config.yaml
    ├── main.tf
    ├── output.tf
    ├── providers.tf
    ├── terraform.tfstate
     ├── terraform.tfvars
      └── variables.tf

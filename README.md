# Ansible Practice

학원에서 진행한 Ansible 실습 내용을 정리한 저장소입니다.

## Environment

- OS : Red Hat Enterprise Linux 10
- Ansible : ansible-core
- Editor : VS Code / Vim
- Virtualization : VMware

## Directory Structure

```
.
├── 00_poweroff
├── 03_adhoc
├── 03_inventory
├── 03_manage
├── 04_multi
├── 04_playbook
├── 04_web-db
├── 05_dev-vars-facts
├── 05_epel
├── 05_exec-ansible-vault
├── 05_facts
├── 05_host_group_vars
├── 05_hwreport
├── 05_manage-vars
├── 05_secret
├── 05_simple_magic
├── 05_variables
├── 05_variables_facts
├── 05_vars-inclusions
├── 06_hosts
├── 06_job_control
├── 06_notify_handlers
├── 06_when_loop
├── 07_files
├── 07_template-hosts
├── 07_template-motd
├── 07_template-ps1
├── 08_project
├── 09_role-collections
├── 09_roles
├── 09_roles_create
└── 09_roles_download
```

## Practice Contents

### Basic
- Inventory 구성
- Ad-Hoc Command
- Playbook 작성
- Multi Playbook

### Variables & Facts
- Variables
- Facts
- Custom Facts
- Host Variables
- Group Variables
- Variable Include
- Ansible Vault

### Playbook
- Condition (when)
- Loop
- Register
- Handlers
- Job Control

### File Management
- copy
- template
- lineinfile
- blockinfile
- SELinux 관리

### Roles & Collections
- Role 생성
- Galaxy Role 다운로드
- Collection 사용
- Role 기반 서비스 배포

### Project
- Playbook 프로젝트 구성
- Task 분리
- 복구(restore) Playbook 작성

## Skills

- Ansible
- YAML
- Jinja2 Template
- SSH
- Linux System Administration
- RHEL 10

## Notes

- 학원 실습 내용을 개인 학습 및 복습 목적으로 정리한 저장소입니다.
- 실습 중 생성되는 로그, 임시 파일 및 Vault Password 파일은 제외하였습니다.

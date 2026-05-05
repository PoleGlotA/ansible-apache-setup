# Ansible Apache Setup

## 📌 Опис
Цей проєкт автоматично встановлює Apache на віддалений сервер через Ansible.

## ⚙️ Вимоги
- Linux / MacOS
- Встановлений Ansible
- SSH доступ до сервера

## 🚀 Кроки запуску

### 1. Клонування
git clone https://github.com/your-username/ansible-apache-setup.git
cd ansible-apache-setup

### 2. Редагування hosts
Вкажіть IP вашого сервера:
[web]
your_server_ip ansible_user=ubuntu

### 3. Запуск playbook
ansible-playbook -i hosts apache.yml

## ✅ Перевірка
Відкрийте в браузері:
http://your_server_ip# ansible-apache-setup

# devops-netology
Byzgaev Netology

# Игнорирование файлов в проекте Terraform

Благодаря настройкам в `.gitignore`, Git будет игнорировать следующие файлы и папки в проекте Terraform:
- Каталог `.terraform` со всеми его содержимым
- Файлы с расширением `.tfstate` и `.tfstate.backup`
- Crash log файлы
- Файлы с расширением `.tfvars`, которые могут содержать чувствительные данные
- Переопределения (`override.tf`, `override.tf.json`) и файлы конфигурации CLI (`.terraformrc`, `terraform.rc`)


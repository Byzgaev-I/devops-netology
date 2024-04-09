<<<<<<< HEAD
Byzgaev Netology
=======
# devops-netology
Byzgaev Netology
>>>>>>> dde727d14c5ac90e363c5b94247447fd9dd89be6


# Игнорирование файлов в проекте Terraform

Благодаря настройкам в `.gitignore`, Git будет игнорировать следующие файлы и папки в проекте Terraform:
- Каталог `.terraform` со всеми его содержимым
- Файлы с расширением `.tfstate` и `.tfstate.backup`
- Crash log файлы
- Файлы с расширением `.tfvars`, которые могут содержать чувствительные данные
- Переопределения (`override.tf`, `override.tf.json`) и файлы конфигурации CLI (`.terraformrc`, `terraform.rc`)


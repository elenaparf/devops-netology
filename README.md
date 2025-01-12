1
# Локальные каталоги .terraform
**/.terraform/*

#Файлы .
tfstate *.tfstate
*.tfstate.*

# Файлы
журнала сбоев crash.log
сбой.*.log

# Исключите все файлы .tfvars, которые могут содержать конфиденциальные данные, такие как
# пароль, закрытые ключи и другие секреты. 
*.tfvars
*.tfvars.json

# Игнорируйте файлы переопределения, поскольку они обычно используются для локального переопределения ресурсов и поэтому
# не проверяются в override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Игнорируйте файлы информации о временной блокировке, созданные terraform apply
.terraform.tfstate.lock.info

# Включить переопределение файлов, которые вы хотите добавить в систему управления версиями, используя шаблон 
# !example_override.tf

# Включите файлы tfplan, чтобы игнорировать вывод команды: terraform plan -out=tfplan
# # пример: *tf plan*

# Игнорируйте файлы конфигурации CLI
.terraformrc
terraform.rc# devops-netology


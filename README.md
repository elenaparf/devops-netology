
#игнорируем папки .terraform и их содержимое
**/.terraform/*
#игнорируем файлы, начинающиеся и заканчивающиеся на tfstate и содержащие tfstate
tfstate *.tfstate
*.tfstate.*
#ингнорируем файл crash.log и файл, начинающийся на crash. и заканчивающийся на .log
crash.log
crash.*.log

#игнорируем все файлы, заканчивающиеся на .tfvars и на .tfvars.json
*.tfvars
*.tfvars.json

#игнорируем файлы override.tf.json, окнчивающиеся на _override.tf и _override.tf.json
override.tf.json
*_override.tf
*_override.tf.json

# игнорируем все файлы .terraform.tfstate.lock.info
.terraform.tfstate.lock.info

# исключаем файлы из игнора по знаку !
# !example_override.tf

# игорируем все файлы, содержащие tf plan
# # пример: *tf plan*

# игнорируем все файлы .terraformrc и terraform.rc
.terraformrc
terraform.rc

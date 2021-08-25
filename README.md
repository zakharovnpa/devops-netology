# devops-netology

#Первое изменение

#Второе изменене

#В  репозиторий terraform при коммитах будут исключены файлы и каталоги:

# Локальных каталогов terraform
** /. terraform / *

# Файлы с информацией о версии terraform.
* .tfstate
* .tfstate. *

# Файлы журнала сбоев
crash.log

# Файлы, которые могут содержать пароли и ключи.
* .tfvars

# Файлы переопределения
override.tf
override.tf.json
* _override.tf
* _override.tf.json

# Включение файлов переопределения по шаблону
! example_override.tf

# Файлы для игнорирования вывода плана команды: terraform plan -out = tfplan
* tfplan *

# Файлы конфигурации CLI
.terraformrc
terraform.rc





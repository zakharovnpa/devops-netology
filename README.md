# devops-netology

#Первое изменение

#Новая строка

#Второе зменене
В репозиторй terraform не попадут файлы:
# Local .terraform directories
**/.terraform/*
>>>>>>> fix

#Из версионного контроля в репозтории terraform на основании шаблонов в .gitignore будут удалены:

# Каталоги с именем terraform, находящиеся в любом количестве вышестоящих директорий с любыми именами и с любым именем в одной нижестоящей поддиректории
** /. terraform / *

# Файлы .tfstate с любым именем
* .tfstate

# Файлы .tfvars с любым именем
* .tfvars

# Файлы, в расширении которого есть имя tfstate, а вторая часть расшреня - с любым именем
#Пример - qwerty.tfstate.zip
* .tfstate. *

# Файлы .log с именем crash
crash.log

# Файлы .tf с именем override
override.tf

# Файлы .tf.json с именем override
override.tf.json

# Файлы  .tf или tf.json c именем, которое содержит _override 
* _override.tf
* _override.tf.json

# Файлы с любым расширением с именем, которое содержит tfplan
* tfplan *

# Скрытые файлы с именем terraformrc
.terraformrc

 # Файлы .rc с именем terraform
terraform.rc

# Добавлять в репозиторий terraform файлы .tf с именем example_override
! example_override.tf



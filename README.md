# devops-netology
#  Игнорироввание с расширением .tfstate files, будут игнорироваться во всех директориях
*.tfstate 
*.tfstate.
# игнорирование фалов crash.log, crash.*.log, одна звездочка — это подстановочный знак, который может соответствовать как нескольким символам, так и ни одному.
crash.log
crash.*.log
# Исключить все файлы c расширением  .tfvars, будут игнорироваться во всех директориях
.tfvars
# Исключить файлы override.tf, override.tf.json
override.tf
override.tf.json
# игнорирование файлов *_override.tf, *_override.tf, одна звездочка — это подстановочный знак, который может соответствовать как нескольким символам, так и ни одному.
*_override.tf
*_override.tf.json
# Игнорироввание с расширением .terraformrc, будут игнорироваться во всех директориях
.terraformrc
# Игнорироввание файла terraform.rc
terraform.rc


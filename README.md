# devops-netology

Первый коммит

## Игнорирование папок и файлов из /Terraform/.gitignore:  

- Папка .terraform/  и ее содержимое  
- Файлы с расширением .tfstate, имя которых содержит *.tfstate.* (например terraform.tfstate.backup) 
- Файл логов crash.log и все файлы по маске crash.*.log (например crash.123.log)  
- Файлы с расширением .tfvars и .tfvars.json  
- Файлы с точным именем override.tf и override.tf.json  
- Файлы, имя которых заканчивается на _override.tf  
- Файлы, имя которых заканчивается на _override.tf.json  
- Файл с именем .terraform.tfstate.lock.info  
- Файл с точным именем .terraformrc  
- Файл с точным именем terraform.rc  

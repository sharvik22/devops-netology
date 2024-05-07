# devops-netology
# hello
# GITHUB
в файле .gitignore каталога terraform игнорируются слудующее: 
**/.terraform/*: -  все файлы и каталоги с именем terraform и их содержимое во всех каталогах
*.tfstate и *.tfstate.*: - файлы с расширениями .tfstate и .tfstate., за которыми следуют любые символы
crash.log и crrash.*.log: - файлы с именем crash.log и файлы, имя которых начинаются с crash и заканчиваются на log
*.tfvars и *.tfvars.json: файлы с расширениями .tfvars и .tfvars.json
override.tf,override.tf.json,*_override.tf, *_override.tf.json -файлы override.tf,override.tf.json и 
файлы в имени который есть _override.tf, *_override.tf.json
.terraformrc, terraform.rc файлы конфигурации CLI

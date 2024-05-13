Благодаря файлу terraform/.gitignore будут проигнорированы:

Все дирректории содержащие .terraform и поддирректории
Все файлы содержащие в имени .tfstate
Все файлы содержащие в имени crash.log
Все конфиденциальные файлы содержащие в имени .tfvars или tfvars.json
Все файлы локального изменения ресурсов override.tf override.tf.json *_override.tf *_override.tf.json
Все файлы конфигурации CLI .terraformrc terraform.rc
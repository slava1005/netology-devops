# netology-devops
## Hei
###Guten Tag
#### Hei World

#### **/.terraform/* Скрытая директория, которую Terraform использует для управления кэшированием, записывает, 
какая рабочая область активна в данный момент, и записывает последнюю известную конфигурацию серверной 
части на случай, если потребуется перенести состояние при следующем запуске. Этот каталог автоматически 
управляется Terraform и создается во время инициализации.
crash.log и crash.*.log Файлы журналов сбоев.

####*.tfvars и *.tfvars.json Исключает все файлы .tfvars, которые могут содержать конфиденциальные данные, 
например пароль, секретные ключи и другие секреты. Они не должны быть частью версии контроль, поскольку 
они представляют собой точки данных, которые потенциально конфиденциальны и подвержены меняться в зависимости 
от окружающей среды.

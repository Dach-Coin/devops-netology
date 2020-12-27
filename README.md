# devops-netology

## Репозитарий для выполнения домашних заданий по курсу "DevOps-инженер"

1. В каталоге Terraform располагается файл .gitignore. В данном файле настроено игнорирование отслеживания VCS git следующих файлов:
    - все файлы, которые будут размещены или созданы в служебном каталоге ".terraform"
    (если полный путь к файлу будет  содержать это имя, то есть - на любом уровне вложенности);
    - все описанное ниже также имеет смысл только для файлов, размещаемых в каталоге "terraform" (на любом уровне вложенности);
    - все файлы, расширение которых равно "tfstate";
    - все файлы, имя которых содержит строку ".tfstate." (с любым расширением);
    - файл с именем "crash.log";
    - файлы с расширением "tfvars";
    - файлы с именем "override.tf" и "override.tf.json";
    - файлы, имя которых содержит и заканчивается на строку "_override" и имеющие расширение "tf";
    - файлы, имя которых содержит и заканчивается на строку "_override.tf" и имеющие расширение "json";
    - файлы, расширение которых равно "terraformrc";
    - файл, имя которого равно "terraform" и расширение "rc".

ДЗ 2.2: произвольная строка, обозначающая изменение в ветке fix
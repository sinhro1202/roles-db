# sinhro1202_infra repository student Alexey M.


## Homework 7 TERRAFORM-2

> * Определен ресурс файервола для terraform-конфигурации.
> * Описан внешний ресурс (IP-адрес для инстанса) в terraform-конфигурации.
> * Реализованы  две отдельные Packer-конфигурации для образов приложения и MongoDB; на их основе были сконфигурированы и проверены соответствующие образы в GCP.
> * terraform-конфигурация была разбита по файлам-модулям, после чего была протестирована эта конфигурация.
> * Реализована модульность для terraform-конфигурации (модули: "app", "db" и "vpc").
> * Протестирована новая модульная конфигурация (проверена успешность её реализации).
> * На основе созданных модулей были реализованы и протестированы два окружения ("stage" и "prod").
> * Были созданы бакеты в сервисе Storage, а также была проверена их доступность.
>
> ## Как запустить проект:
> * На основе Packer-конфигураций "app.json" и "db.json" создать в GCP необходимые образы.
> * Реализовать prod и stage инстансы на основе terraform-конфигураций в соответствующих ветках и проверить успешность их выполнения и запуска искомых приложений. Для prod-кейса нужно поменять IP машинки на свой.
> * Cоздать бакет на основе terraform-конфигурации "storage-bucket.tf", проверить доступность и успешность его создания.
>
> ## Как проверить работоспособность:
> * Описанные выше три операции из вкладки "Как запустить проект" должны успешно выполняться, реализовывая поставленные задачи в рамках текущего ДЗ.
>
> ## PR checklist
> * [x]  Выставил label с темой домашнего задания
-

### Additional tasks with *

- Created backend.tf file for store tf state file in remote backet.
- Checked terraform eorks with remote tf state files.

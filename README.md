# Ansible
Обновление CentOS 7, исключая пакет time.

Остаётся 2 старых версии ядра, не считая текущее активное.

Перезагрузка после обновления написана в handler, для локального хоста модуль reboot неперменно делает fail.

В inventory можно дописать ip удалённого хоста, для него будет подключение по ssh, ключ ожидается в ~/.ssh/id_rsa 

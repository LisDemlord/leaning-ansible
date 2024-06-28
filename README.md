check_dependecies.sh - скрипт для проверки наличие необходимых пакетов для сборки LFS \n
hosts.ini            - файл инвентаризации в формате INI \n
hosts.ini            - файл инвентаризации в формате YAML \n
install-python.yml   - playbook для установки python 3.12.4 \n
nginx.cong.j2        - файл конфигурации для nginx на VM (сгенерирован chatGPT и ни как не проверялся) \n
nginx.yml            - playbook для установки и настройки nginx \n
output.txt           - файл с данными вывода в ходе выполнения run-scripts.yml \n
run-scripts.yml      - playbook для выполнения скрипта check_dependecies.sh на удаленных машинах \n
test_setup.yml       - playbook для тестирования модуля setup \n

Все скрипты и playbook'и протестированы и нормально работают на 2 виртульных машинах (Oracle Linux 9.4) в gnome-box

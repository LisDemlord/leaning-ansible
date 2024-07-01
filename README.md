- **check_dependecies.sh**: Скрипт для проверки наличия необходимых пакетов для сборки LFS.
- **hosts.yml**: Файл инвентаризации в формате YAML.
- **install-python.yml**: Playbook для установки Python 3.12.4.
- **nginx.conf.j2**: Файл конфигурации для nginx на VM (сгенерирован ChatGPT и не проверялся).
- **nginx.yml**: Playbook для установки и настройки nginx.
- **output.txt**: Файл с данными вывода в ходе выполнения `run-scripts.yml`.
- **run-scripts.yml**: Playbook для выполнения скрипта `check_dependecies.sh` на удалённых машинах.
- **test_setup.yml**: Playbook для тестирования модуля setup.

## Все скрипты и playbook'и протестированы и нормально работают на 2 виртульных машинах (Oracle Linux 9.4) в gnome-box

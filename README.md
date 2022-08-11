"# my_task" 
 includes trilom/file-changes-action@v1.2.3
 
 Detect modified and added files in the repository, create json-files,
 create  3 params with file extension, environment name and configuration file name
 creates environments based on on changed files.
 
 Українська
 
  Тригером для Github Actions є push до репозиторію зміненого конфігураційного файлу txt формата. Тригер реагує тільки на модифіковані , а не на нові файли. Розширення  файлу повинно бути формату txt, а не Txt, чи tXt. Назва файла конфігурації включена в назву проекту та назву віртуального середовища Python. Для коректного використання  Ansible потрібно налаштувати файл inventory - hosts.ini. Кількість розгорнутих видалених хостів дорівнює кількості модифікованих конфігураційних файлів.
 
 English
 
  The trigger for Github Actions is push to the repository of the modified txt format configuration file. The trigger only responds to modified, not new, files. The file extension must be txt, not Txt, or tXt. The configuration file name is included in the project name and the name of the Python virtual environment. To use Ansible correctly, you need to configure the inventory file - hosts.ini. The number of remote hosts deployed is equal to the number of modified configuration files.
  
  Deutsch
  
  Der Auslöser für Github-Aktionen wird in das Repository der Konfigurationsdatei für das geänderte txt-Format verschoben. Der Trigger reagiert nur auf geänderte, nicht auf neue Dateien. Die Dateierweiterung muss txt, nicht Txt oder tXt sein. Der Konfigurationsdateiname ist im Projektnamen und im Namen der virtuellen Python-Umgebung enthalten. Um Ansible richtig zu verwenden, müssen Sie die Inventardatei - hosts.ini konfigurieren. Die Anzahl der bereitgestellten Remote-Hosts entspricht der Anzahl der geänderten Konfigurationsdateien.

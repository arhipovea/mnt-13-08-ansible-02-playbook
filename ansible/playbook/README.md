# Clickhouse, Vector on CentOS7

Этот плейбук устанавливает Clickhouse, Lighthouse и Vector. 

## Playbook Structure

Структура плейбука:

```
playbook
├── group_vars
│   ├── clickhouse.yml
│   ├── lighthouse.yml
│   └── vector.yml
├── inventory
│   └── prod.yml
├── site.yml
└── README.md
```

## Settings

- `clickhouse_version`: версия Clickhouse
- `clickhouse_packages`: имена пакетов для установки
- `vector_version`: версия Vector
- `vector_config`: конфиг vector
- `lighthouse_dest`: файлы Lighthouse
- `lighthouse_uri`: uri Lighthouse
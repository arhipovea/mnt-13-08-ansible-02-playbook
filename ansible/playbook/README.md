# Clickhouse, Vector on CentOS7

Этот плейбук устанавливает Clickhouse и Vector. 

## Playbook Structure

Структура плейбука:

```
playbook
├── group_vars
│   ├── clickhouse
│   │   └── vars.yml
│   └── vector
│       └── vars.yml
├── inventory
│   └── prod.yml
├── site.yml
└── README.md
```

## Settings

- `clickhouse_version`: версия Clickhouse
- `clickhouse_packages`: имена пакетов для установки
- `vector_version`: версия Vector
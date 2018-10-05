## Install

```bash
npm install -g @cthru/devsql
```

## Use

dbmigration.json

```json
{
  host: 'dbhost.com',
  user: 'dbuser',
  password: 'dbpass',
  database: 'database',
  tables: ['table1', 'table2'],
  extendedInsert: true,
  addDropTable: true,
  addLocks: true,
  disableKeys: true
}
```

`devsql dbmigration.json`  
will result in  
`dbmigration.date_time.sql`

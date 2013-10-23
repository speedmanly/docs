---
layout: api-command 
language: Ruby
permalink: api/ruby/table_list/
command: table_list
github_doc: https://github.com/rethinkdb/docs/edit/master/2-query-language/api/ruby/manipulating-tables/table_list.md
related_commands:
    table_create: table_create
    table_drop: table_drop/
---

{% apibody %}
db.table_list() → array
{% endapibody %}

List all table names in a database. The result is a list of strings.

__Example:__ List all tables of the 'test' database.

```rb
r.db('test').table_list().run(conn)
```


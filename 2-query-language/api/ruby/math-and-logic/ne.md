---
layout: api-command 
language: Ruby
permalink: api/ruby/ne/
command: ne 
github_doc: https://github.com/rethinkdb/docs/edit/master/2-query-language/api/ruby/math-and-logic/ne.md
related_commands:
    '&': and/
    '|': or/
    eq: eq/
---

{% apibody %}
value.ne(value) → bool
{% endapibody %}

Test if two values are not equal.

__Example:__ Does 2 not equal 2?

```rb
r.expr(2).ne(2).run(conn)
```


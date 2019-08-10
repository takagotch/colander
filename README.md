### colander
---
https://docs.pylonsproject.org/projects/colander/en/latest/

```py
import colander
import pprint

class Friend(colander.MappingSchema):
  rank = colander.SchemaNode(
    colander.Int(),
  )
  name = colander.SchemaNode(
    colander.String(),
    )
class SpecialFriend(Friend):
  iwannacomefirst =colander.SchemaNode(
    colander.String(),
    insert_before='rank',
    )
  another = colander.Schemanode(
    colander.String(),
    )
class SuperSpecialFriend(SpecialFriend):
  iwannacomefirst = colander.SchemaNode(
    colander.Int(),
  )
frind = SuperSpecailFriend()
pprint.pprint([(x, x.typ) for x in friend.children])

import colander
import pprint
class One()
class Two()
class Three(One, Two)
  b = colander.SchemaNode(colander.Bool())
  d = colander.SchemaNode(colander.Bool())
s = Three()
pprint.pprint([(x, x.typ) for x in s.children])
```

```
```

```
```



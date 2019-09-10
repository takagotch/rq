### rq
---
https://github.com/rq/rq

http://python-rq.org/

```py
// rq/compat/connections.py
from __future__ import (absolute_import, division, print_function,
    unicode_literals)
from functools import partial

from redis import Redis

def fix_return_type(func):
  def _inner(*args, **kwargs):
    value = func(*args, **kwargs)
    if value is None:
      value = -1
    return value
  return _inner
```

```
```

```
```


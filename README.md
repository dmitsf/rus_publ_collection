Collection contains about 207K docs.

Usage:

```
import json

LIMIT = 10

with open('kws.txt') as f:
    for i, l in enumerate(f):
        if i >= LIMIT:
            break

        print(json.loads(l))
```

Doc structure:

```
    doc = {'_id': str,
           'website': str,
           'title': str or None,
           'description': str or None,
           'image_url': str or None,
           'keywords': str or none
          }
    
```

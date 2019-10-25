### NLTK
---
https://github.com/nltk/nltk

http://www.nltk.org/


```py
// nltk/test/inference_fixt.py

def setup_module(module):
  from nose import SkipTest
  from nltk.inference.mace import Mace
  
  try:
    m = Mace()
    m._find_binary("mace4")
  except LookupError:
    raise SkipTest(
      "Mace4/Prover9 is not available so inference.doctest was skipped"  
    )

```

```
```

```
```


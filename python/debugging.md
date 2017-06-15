- https://docs.python.org/3.6/library/traceback.html

```
import traceback
traceback.print_stack()
```

- https://github.com/gotcha/ipdb

```
import ipdb
ipdb.set_trace()
ipdb.set_trace(context=5)  # will show five lines of code
                           # instead of the default three lines
ipdb.pm()
ipdb.run('x[0] = 3')
result = ipdb.runcall(function, arg0, arg1, kwarg='foo')
result = ipdb.runeval('f(1,2) - 3')
```

- https://docs.python.org/3.6/library/pdb.html

```
import pdb; pdb.set_trace()
```

- http://ipython.readthedocs.io/en/stable/interactive/reference.html#embedding

```
from IPython import embed
embed() # this call anywhere in your program will start IPython
```

- https://docs.python.org/3.6/library/functions.html

```
dir()
locals()
globals()
vars()
x.__dict__
```

### Profiling

- https://docs.python.org/2/library/profile.html
- `python -m cProfile -s cumtime main.py`

# co_py
> Python Wrapper around Codeforces API


## Install

`pip install co_py`

## Usage

```python
from co_py.core import CFApi
```

###### Without api_key and secret

```python
cf = CFApi()
```

###### With api_key and secret

```python
import os
```

```python
api_key = os.environ.get('API_KEY')
secret = os.environ.get('SECRET')
```

```python
cf = CFApi(api_key=api_key, secret=secret)
```

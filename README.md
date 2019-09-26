# PYZEDIS <img src="https://img.shields.io/github/stars/drbh/zedis.svg" />

<img src="https://github.com/drbh/zedis/blob/master/public/zedislogo.png" alt="Logo">

[learn more](https://github.com/drbh/zedis)

# Install
```
pip install pyzedis
```


# Use

```
Python 3.7.3 (default, Mar 27 2019, 09:23:15) 
[Clang 10.0.1 (clang-1001.0.46.3)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import pyzedis
>>> c = pyzedis.ZedisClient()
>>> c.zget("david")
```

# Functions

### `zset(key, value)`
### `zset_json(key, value)`
### `zget_json(key)`
### `zget(key)`
### `zkeys()`
### `zclear()`
### `zflush()`
### `zdel(key)`
### `zpre(prefix)`

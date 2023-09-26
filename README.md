# redis-wheel

To install the pre-compiled Redis binaries:

```sh
pip install redis-wheel==<redis-version>
```

Supported `redis-version`:

- `5.0.7`
- `6.0rc2`
- `6.2.5`

Supported platforms:

- `manylinux2010_x86_64`
- `manylinux2010_i686`
- `macosx_10_15_x86_64`

Supported python versions:

- `cp35`
- `cp36`
- `cp37`
- `cp38`
- `cp39`

To get the paths of pre-compiled Redis binaries:

```python
import redis_wheel

redis_wheel.REDIS_SERVER_PATH  # redis-server
redis_wheel.REDIS_CLI_PATH     # redis-cli
```

# redis-wheel

To install the pre-compiled Redis binaries:

```sh
pip install redis-wheel==<redis-version>
```

Supported versions of Redis:

- `6.2.5`

Supported platforms:

- `manylinux_2_28_x86_64`
- `macosx_14_0_x86_64`
- `macosx_14_0_arm64`

Supported python versions:

- `cp39`
- `cp311` (except mac x64)

To get the paths of pre-compiled Redis binaries:

```python
import redis_wheel

redis_wheel.REDIS_SERVER_PATH  # redis-server
redis_wheel.REDIS_CLI_PATH     # redis-cli
```

# kilroy-module-client-py-sdk

SDK for kilroy module clients in Python 🧰

## Installing

Using `pip`:

```sh
pip install kilroy-module-client-py-sdk
```

## Usage

```python
from kilroy_module_client_py_sdk import ModuleService

service = ModuleService(host="localhost", port=11000)

await service.get_metadata()
```

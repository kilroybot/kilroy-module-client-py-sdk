# Usage

You can use this package to interact with modules.

The easiest way is to use the `ModuleService` class.
It provides a high-level interface to all the methods of the service.
All methods are either coroutines or async iterators.

Here's an example:

```python
from kilroy_module_client_py_sdk import ModuleService

service = ModuleService(host="localhost", port=10000)

await service.get_metadata()
```

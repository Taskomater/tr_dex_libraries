# tr_dex_libraries

Provides `jar` and their respective `dex` files for common libraries that can be loaded in [Tasker] app with [`DexClassLoader`](https://developer.android.com/reference/dalvik/system/DexClassLoader) via `Java Function` action. The [`tx_dex_utils`](https://github.com/Taskomater/tx_dex_utils) project is provides utility tasks to easier load `dex` files.

The library `jar` files are currently manually downloaded from respective library's published repo, like `maven`, etc and then pushed. The `jar` files need to converted to `dex` files with the command `dx --dex --output=/path/to/dex /path/to/jar` to be loadable by `DexClassLoader`. The `dex` files are built with a github workflow for security reasons instead of locally.


[Tasker]: https://tasker.joaoapps.com

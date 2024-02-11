# CosmoEngineProfiler


--- 
HOWTO:

```cpp
#include <profiling/Profiler.hpp>

// inside Any function
int anyFunc()
{
	PROFILE_FUNCTION();
	// Any scope
	{
		PROFILE_SCOPE("This is scope for file loading");
	}
}
```

1. Then go to `out/x64-debug` run .exe file
2. Drag and drop `results.json` into `edge://tracing/`
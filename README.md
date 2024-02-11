# CosmoEngineProfiler


--- 
HOWTO use:

```cpp
#include <Profiler.hpp>

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
3. Happy profiling!
![https://github.com/CyberKoalaStudios/ProfilerLibrary/blob/75f43edc2a633bafc3d839b766553fb171ae7e97/screenshots/howto.png](https://github.com/CyberKoalaStudios/ProfilerLibrary/blob/75f43edc2a633bafc3d839b766553fb171ae7e97/screenshots/howto.png)

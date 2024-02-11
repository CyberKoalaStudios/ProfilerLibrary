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

<blockquote class="imgur-embed-pub" lang="en" data-id="a/SQCbHlf" data-context="false" ><a href="//imgur.com/a/SQCbHlf"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

!(https://imgur.com/a/SQCbHlf)[https://imgur.com/a/SQCbHlf]
![screenshors](https://imgur.com/a/SQCbHlf)
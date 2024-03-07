# ProfilerLibrary (CE Profiler)

[![CMake on multiple platforms](https://github.com/CyberKoalaStudios/ProfilerLibrary/actions/workflows/cmake-multi-platform.yml/badge.svg)](https://github.com/CyberKoalaStudios/ProfilerLibrary/actions/workflows/cmake-multi-platform.yml)

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

---
## Features at a Glance
* Platform Agnosticism: ProfilerLibrary is designed to seamlessly integrate with various operating systems, from Windows and Linux to macOS, providing a unified profiling experience.

* Minimal Overhead: Worried about the impact on your application's performance? Fear not!  ProfilerLibrary is engineered to impose minimal overhead, ensuring that your profiling efforts don't compromise the performance gains you're aiming for.

* Detailed Insights: Dive deep into your code with ProfilerLibrary's detailed insights. Identify CPU bottlenecks, memory leaks, and other performance issues across different platforms, enabling targeted optimizations.


Getting Started with ProfilerLibrary
Ready to harness the power of cross-platform profiling in your C++ projects? Follow these steps to integrate  ProfilerLibrary into your development workflow:

* Installation: Begin by installing ProfilerLibrary using the provided instructions for your preferred build system.

* Instrumentation: Instrument your code by adding profiling markers where needed.  ProfilerLibrary provides easy-to-use macros or API calls to annotate specific sections of your code for profiling.

* Compile and Run: Rebuild your project with profiling enabled and run it on different platforms. ProfilerLibrary will capture performance data during runtime.

* Analyze Results: Use the profiling results to identify areas for improvement. Tackle performance bottlenecks, optimize critical functions, and enhance your code's efficiency.

### Conclusion
In the ever-evolving landscape of C++ development, cross-platform profiling is a must-have for those aiming to deliver top-tier performance across diverse environments.  ProfilerLibrary stands out as a reliable ally, offering a comprehensive suite of tools to elevate your code to new heights.

Embrace the power of cross-platform profiling today and watch your C++ applications perform seamlessly across Windows, Linux, macOS, and beyond! Happy coding!

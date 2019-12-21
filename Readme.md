<h1>Arduino Nano</h1>

<p>
This is an Arduino-project with IntelliSense, Minimal Rebuild and Multi-Processor-Compilation.<br />
The build-script is for Arduino Nano, but it can be easily adapted to other chipsets.<br />
You just have to enable verbose output in the Arduino IDE and change the compiler-flags,<br />
include-directories and source-files in the project-file.<br />
</p><br />

```cpp
//==========
// Main.cpp
//==========

#include <Arduino.h>

extern "C" void setup()
{
Serial.begin(9600);
}

extern "C" void loop()
{
delay(100);
}
```
<br /><br />

# Stopwatch
*Copyright (C) 2019 David Capello*

[![MIT Licensed](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.txt)

Outputs the time elapsed since the `Stopwatch()` constructor or the
last `watch()`/`reset()` call.

Usage:

```c++
{
   Stopwatch a;
   ...
   a.watch("first algorithm");
   ...
   a.watch("second algorithm");
   ...
   a.watch("third algorithm");
}
```

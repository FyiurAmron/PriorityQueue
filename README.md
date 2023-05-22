# PriorityQueue

Code directly ported from:
https://github.com/dotnet/runtime/blob/release/6.0/src/libraries/System.Collections/src/System/Collections/Generic/PriorityQueue.cs

Provided as a drop-in replacement in scenarios where .NET 6 (or newer) system library is not available (yes, Unity, I'm looking at you :) - it currently uses C# 9.0 features, but can be easily adapted to lower C# version (by simply hacking away the offending helper code).

Original code licensed to the .NET Foundation under one or more agreements.
This file is licensed to you transitively under the MIT license.

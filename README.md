## Overview

Boost.Atomic is a library that provides atomic
data types and operations on these data types, as well as memory
ordering constraints required for coordinating multiple threads through
atomic variables. It implements the interface as defined by the C++11
standard, but makes this feature available for platforms lacking
system/compiler support for this particular C++11 feature.

Users of this library should already be familiar with concurrency
in general, as well as elementary concepts such as "mutual exclusion".

The implementation makes use of processor-specific instructions where
possible (via inline assembler, platform libraries or compiler
intrinsics), and falls back to "emulating" atomic operations through
locking.

## License

* Copyright (c) 2009 Helge Bahmann
* Distributed under the Boost Software License, Version 1.0. (See accompanying file LICENSE_1_0.txt or copy at http://www.boost.org/LICENSE_1_0.txt)

## Contact & Support
* [Post Issue Online](https://github.com/vintage-wang/jwrapper/issues/new)
* vintage.wang@gmail.com

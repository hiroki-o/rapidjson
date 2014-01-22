about this project
=========

This is a custom modification of rapidjson ( http://code.google.com/p/rapidjson/ ).


Readme
=========

Rapidjson v0.1

Copyright (c) 2011 Milo Yip (miloyip@gmail.com)

http://code.google.com/p/rapidjson/

19 Nov 2011

1. Introduction
Rapidjson is a JSON parser and generator for C++. It was inspired by rapidxml http://rapidxml.sourceforge.net/
Rapidjson is small but complete. It supports both SAX and DOM style API. The SAX parser is only a half thousand lines of code.
Rapidjson is fast. Its performance can be comparable to strlen(). It also optionally supports SSE2/SSE4.1 for acceleration.
Rapidjson is self-contained. It does not depend on external libraries such as BOOST. It even does not depend on STL.
Rapidjson is memory friendly. Each JSON value costs exactly 16/20 bytes for 32/64-bit machines (excluding text string). By default it uses a fast memory allocator, and the parser allocates memory compactly during parsing. 

For the full features please refer to the user guide.

JSON(JavaScript Object Notation) is a light-weight data exchange format.
More information about JSON can be obtained at
http://json.org/
http://www.ietf.org/rfc/rfc4627.txt

2. Installation

Rapidjson is a header-only C++ library. Just copy the rapidjson/include/rapidjson folder to system or project's include path.

To build the tests and examples,
1. obtain premake4 http://industriousone.com/premake/download
2. Copy premake4 executable to rapidjson/build
3. Run rapidjson/build/premake.bat on Windows, rapidjson/build/premake on Linux or other platforms
4. On Windows, build the solution at rapidjson/build/vs2008/ or /vs2010/
5. On other platforms, run GNU make at rapidjson/build/gmake/ (e.g., make -f test.make config=release32, make -f example.make config=debug32)
6. On success, the executable are generated at rapidjson/bin



License
=========

The MIT License (MIT)

Copyright (C) 2011 Milo Yip

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


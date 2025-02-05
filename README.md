# Font-Awesome-WPF

WPF & UWP controls for the iconic font and CSS toolkit Font Awesome.

Font Awesome: http://fortawesome.github.io/Font-Awesome/
- Current Version: v4.7.0

## WPF

[Font-Awesome-WPF README](README-WPF.md)

**How to build?**
1. Init the submodule "Font-Awesome" (in order to get file `FontAwesome.otf`)
 `git submodule update --progress --init`
2. Open the solution with Visual Studio (2022+), and then build it.

**How to get the NuGet package?**
1. Build the solution with `Release` configuration
2. Select the project `FontAwesome.WPF` in the Solution Explorer, right click and then click `Pack`
The .nuget file is generated into $OutputDir\$


## License

The MIT License (MIT)

Copyright (c) 2014-2023 Tanzi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


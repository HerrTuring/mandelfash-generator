# Mandelfash Generator

## Description

This project is just a simple console C++ aplication that after run outputs a 2D slice of the mandelfash fractal to a file called "mandelfash.bmp".

This runs with high precision math (using Boost C++ Library) and many small optmizations to decrease the processing time.

To get a different slice of the mandelfash it is necessary to just change the Z variable in one of the first lines of the main function.

This was originally coded by demand for Dave Fashenpour on 2018 as a test and work-in-progress to his idea of an easy-to-use DLL to calculate the mandelfash slices with multi-threading (implemented in another project later).

## Usage

Just open the Visual Studio project in VS 2022 and just compile and run.

Then leave the computer and do something else, it will take quite a while. There are commented lines at the start and end of the main function that can be used to show timestamps before the proccess starts and after it completes.

## Credits

Dave Fashenpour (Mathematician/Code Engineer): The contractor for this project and orginal coder that had a version of this calculator done in Basic which was used as an example on how to make this. This source was uploaded publicly with his permission.

## MIT License

Copyright (c) 2023 Erik Marques Schroeder

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

# JSONValidate
JSON validator in C#

# Basic Introduction
This tool can do 3 tasks:

- -create : Will create a .json file with the expiration date [1 year as default],
- -validate : Checks the .json file included with the filepath,if not valid,will throw a error message incidating the .json file is invalid,if correct,will continue the script.
- -replace : Replaces the file values [for a example: creation date,expiration value (something like 2024(y/year)05(m/month)02(d/day)0010(hour and minute,basically 00:00),202405020010

# Required DLL'S
- Newtonsoft.Json



# License
MIT License

Copyright (c) 2023 BGR2

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

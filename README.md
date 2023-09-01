# Welcome to Tracktable-Data!

Tracktable-Data is a supplimental data package for the Tracktable library. Refer to the
Tracktable [documentation](https://tracktable.readthedocs.org) and [Github repository](https://github.com/sandialabs/tracktable)
for more information on Tracktable's capabilities and usage.

## Usage
Below are example of how to use, `retrieve()`, the only function in the `tracktable-data` package.

```python
from tracktable_data.data import retrieve

# Retrieve file with a name
filepath = retrieve(filename="SampleFlightsUS.csv") # Returns a string

# Retrieve all files with a matching extension
filepathss = retrieve(file_ext=".csv") # Returns a list of strings

# Retrieve all files
all_files = retrieve() # Returns a dictionary

# See all files that can be retrived
retrieve(print_filenames=True)

# See all file extensions that can be retrived
retrieve(print_extensions=True)

```

## Copyright Notice

Copyright (c) 2014-2023 National Technology and Engineering
Solutions of Sandia, LLC. Under the terms of Contract DE-NA0003525
with National Technology and Engineering Solutions of Sandia, LLC,
the U.S. Government retains certain rights in this software.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

1. Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
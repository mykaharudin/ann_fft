# ann_fft

Ann_fft is a Python library that performs 1D FFT-based convolution for large data arrays. It can handle multi-gigabyte datasets and outperform numpy.fft.fft due to its ability to work with large arrays without consuming a significant amount of memory.

## Features

- Conduct 1D FFT-based convolution efficiently
- Handles large datasets with multi-gigabyte sizes
- Faster execution compared to numpy.fft.fft
- Memory-efficient and doesn't consume significant memory

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install ann_fft.

<br>
Usage
Here is an example of how to use ann_fft:

import ann_fft

# Create two 1D data arrays (data1 and data2) of large sizes
data1 = ...
data2 = ...

# Perform FFT-based convolution between data1 and data2
result = ann_fft.fft_convolve(data1, data2)

# result contains the result of the FFT-based convolution

<br>
Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

License
MIT

<s>Feel free to modify this template based on your requirements..</s>
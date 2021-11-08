<p align="center">
	<img src="https://github.com/tienthanhdhcn/VnAPE/blob/main/VnAPE.png" width="200">
</p>

# Automatic Post-Editing for Vietnamese
We release the first large-scale datasets including in-domain and out-of-domain data for automatic post-editing (APE) for Vietnamese in which we aim at the task of automatic post-editing when translating Chinese novels to Vietnamese.

We show how the datasets got constructed and were utlised to train APE models in our **[paper](https://arxiv.org/abs/2104.12128)**:

    @article{VietAPE,
    title     = {Automatic Post-Editing for Vietnamese},
    author    = {Vu, Thanh and Nguyen, Dai Quoc},
    conference   = {Proceedings of ALTA 2021},
    year      = {2021}
    }

**Please CITE** our paper when the datasets are used to help produce published results or incorporated into other software.

## Datasets

Data | #Sentence pairs | Size | URL
---|---|---|---
In-domain | ~5M | 440MB | [download](https://drive.google.com/file/d/1rLdjJxysU19IVRyQ2Xlfwd6nOGhN9ATV/view?usp=sharing)
Out-of-domain | ~5M | 440MB | [download](https://drive.google.com/file/d/1wABbghhbiXv_TgTLfhrXVpLfCf-GTk-9/view?usp=sharing)

## Pre-trained models

A simple web-interface demo of post-editing is included and available to download with the model
Model | Data | Demo? | Size | URL 
---|---|---|---|---
Transformer-large| Indomain | Yes | 2.5G | [download](https://drive.google.com/file/d/15AAGfaKMFZIB1q3cUihtfarG5lPGwfIy/view?usp=sharing)


# License
    
    MIT License

    Copyright (c) 2021 Thanh Vu

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

# solutions
 
## Installation

### Windows

#### cocoapi
[source](https://medium.com/@abinovarghese/installing-coco-api-in-windows-python-9b4dfc3812ef)

1. Go to the official repo: https://github.com/cocodataset/cocoapi
2. Download zip
3. In the PythonAPI directory, comment out: ```extra_compile_args=[‘-Wno-cpp’, ‘-Wno-unused-function’, ‘-std=c99’]```
4. In the PythonAPI directory, run: ```python setup.py build_ext install``` 

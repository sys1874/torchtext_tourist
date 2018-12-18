# torchtext_tourist
一个简单的torchtext 使用教程
## 处理过程
```
preprocess   -> list
add in Example 
build Dataset
build batch -> process ->|pad
                         |numericalize ->| string to int 
                                         | postprocess
                                         | tensor()
```

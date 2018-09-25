# torchtext_tourist
一个简单的torchtext 使用教程，torchtext这东西瞎鸡儿设计的吧，只能强行这么使用了。
## 处理过程
'''
preprocess   -> list
add in Example 
build Dataset
build batch -> process ->|pad
                         |numericalize ->| string to int 
                                         | postprocess
                                         | tensor()
'''
```
neusum
├── code
│   └── NeuSum
│       └── neusum_pt
│           ├── neusum
│           └── PyRouge
└── data
    └── cnndm
        ├── dev
        ├── glove
        ├── models
        └── train
```

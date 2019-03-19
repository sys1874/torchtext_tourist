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
                                       

Iterator
参数：
sort_key
train
repeat
shuffle
sort
sort_within_batch

__iter__
init_epoch -> create_batches(self.batches=yiel minibatch(lsit)) -> self.data()  sort || shuffle
              minibatch -> sort_within_batch
              Batch(minibatch)
```

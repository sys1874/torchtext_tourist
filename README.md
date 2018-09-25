# torchtext_tourist
一个简单的torchtext 使用教程，torchtext这东西瞎鸡儿设计的吧，只能强行这么使用了。
## 处理过程<br />
preprocess   -> list<br />
add in Example <br />
build Dataset<br />
build batch -> process ->|pad<br />
                         |numericalize ->| string to int <br />
                                         | postprocess<br />
                                         | tensor()<br />

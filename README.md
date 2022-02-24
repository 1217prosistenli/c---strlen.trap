# c---strlen.trap
c++->strlen
##c++ --》strlen使用注意点##
在使用字符串函数strlen的时候，##要注意##它返回的类型是size_t
##typedef unsigned int size_t##
其实返回的是一个无符号int
至于为什么会返回unsigned int，因为字符串的大小不会为负

# Accelerated-C++

这是关于《Accelerated C++》的学习笔记。

## 第三章：使用批量数据
<ios> streamsize : 表示长度
<iomanip> setprecision :  控制输出的位数
cout.precision   成员函数
>`streamsize prec = cout.precision(3);  //把输出精度设为3，返回初始精度
>cout<<number
>cout.precision(prec)  //把输出精度设为初始精度`

如果两个以上的字符串直接量仅仅是被空格符分开，那么这些字符串直接量会被自动连接到一起。

>`cout<<"hello"`
>>`"world"`

使用库定义的size——type类型表示容器长度
typedef type name  把name定义为type的替代名

<stdexcept> domain_error（“”）:  抛出异常
参数是初始值等于参数的局部变量

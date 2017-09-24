## 结构体初始化
```
type Hello struct{
  A int
  B string
}

H1 := new(Hello) // 返回实例化后的对象的指针
H2 := &Hello{} // 同H1
H3 := Hello{} // 返回变量
```

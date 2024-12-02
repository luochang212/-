# 小王加班没

一道考公题是这样的：

![](/img/item.png)

```
小王没有吃饭，所以小王今天加班了。 得出上述结论的前提是：

A. 所有今天没有加班的人都吃了饭
B. 所有没有吃饭的人今天都加班了
C. 所有今天加班的人都没有吃饭
D. 所有吃了饭的人今天都没有加班
```

你觉得哪个选项对呢？

B 很容易看出来是对的，争议点在于 A 对不对。

---

正确答案是：A 和 B

因为 A 和 B 互为逆否命题，所以它们是等价的：

- 原命题：P → Q
- 逆否命题：~Q → ~P


另附使用代码的证明方式：[main.ipynb](/main.ipynb)

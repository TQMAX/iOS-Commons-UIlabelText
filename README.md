# iOS-Commons-UIlabelText
iOS-Commons-UIlabelText

### 工具汇总贴：[iOS常用扩展工具类（只为你的开发能更得心应手~）](https://tqmax.github.io/2018/01/07/iOS常用扩展工具类（只为你的开发能更得心应手~）/)

#### 我们会经常遇到一些一个Label上显示多行文字又要不能过于紧密的需求，这样子，这个类的作用的来了~

```objc

    //用法如下：

    //我这里只列举了修改行距的用法，另外两个雷同的
    cell.textLabel.text = @"芝麻信用680分及以上，押金为总零售价的20%。\n芝麻信用680分以下，押金为总零售价的30%。\n会员期内无限换戴。\n邮费自理（每次邮寄平台代收30）。";
    [UILabel changeLineSpaceForLabel:cell.textLabel WithSpace:10];
 
```

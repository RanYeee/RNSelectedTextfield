# RNSelectedTextfield


## 用法

``` objc
RNSelectedTextfield *selectTextfield = [[RNSelectedTextfield alloc]initWithFrame:CGRectMake(0, 0, self.view.bounds.size.width/2, 30)];
    selectTextfield.autoSaveCache = YES; //是否自动存储（设为YES的话，输入完成后会自动缓存起来）也可以用[selectTextfield saveInputCache]手动保存
    selectTextfield.center = self.view.center; 
    selectTextfield.cacheInputTextLimit = 5; //缓存输入个数
    [self.view addSubview:selectTextfield];

```
## 安装

RNSelectedTextfield is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "RNSelectedTextfield"
```

## 作者

xuar ,xuar@hori_gz.com

## 许可

MIT


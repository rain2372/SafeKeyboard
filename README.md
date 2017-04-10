# SafeKeyboard
H5安全键盘

## 应用场景
- 数字密码 (789465)
- 银行卡 (6214 8301 8552 1452)
- 有效期 (10/23)
- CVV2 (223)
- 身份证(4856457987444565464X)
- 金额 (9.81)

## 关键点
- 键盘类
- 按钮类
- 按钮跟键盘关联
	- 按钮展示顺序
	- 按钮点击回调
	- 按钮与输入框绑定
	- 键盘位置置底
	- 键盘与文本关系

## API

### input 属性：
- type 
- placeholder
- max-length
- autofocus
- value
- pattern [todo]
- autosubmit(max-length)


方法属性:
- callback


方法：
- create
- destroy
- show
- hide

```

## 解决问题
- 图片svg
- meta梳理
- fastclick
- 禁止长按
- 动画、缩放

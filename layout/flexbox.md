# 属性
```css
display: flex;
```

```css
/* flex-direction: row;
   flex-wrap: wrap; 

  上述两个属性可以通过下面一个属性表示
*/
flex-flow: row wrap;
```

```css
flex: 1;
```

`flex`指定的是无单位的比例。后面可以有第二个参数（指定最小值）。比如：
```css
flex: 1 200px;
```
意思是：在一开始，每个 flex item从可用的空间中分配 200px，之后，剩余的可用空间按照比例来分配。

# flex短记法与长记法
flex 是短记写法。它可以通过三个不同的属性来实现。
- 无单位的比例值，可以通过属性 `flex-grow` 指定
- 第二个无单位的比例值。`flex-shrink`。当`flex item`溢出`flex container`时，指定从每个`flex item`的大小中提取多少才能阻止这个溢出。
- 最小值。可以通过属性`flex-basis`指定

# 水平与垂直对齐
```css
align-items: center
```
控制 `cross axis`方向上的`flex item`排列。
- 默认值：`stretch`。拉升填满整个`cross axis`方向
- `center`值会导致每个项维持内部尺寸，同时在`cross axis`方向上居中
- 还有类似`flex-start`和`flex-end`的属性

当个`flex item`中，属性`align-self`会覆盖`align-items`属性


```css
justify-content: space-around;
```
控制`main axis`方向上`flex item`排列。
- 默认值：`flex-start`。从`main-start`开始排列
- `flex-end`，将item设置到`main-end`位置
- `center`居中
- `space-around`：在`main axis`方向上为每个`flex item`平均分配空间，同时`main start`和`main end`会留有一定的空间
- `space-between`：和`space-around`类似，除了`main start`和`main end`不会留有一定的空间


# 排序
```css
order: 1
```
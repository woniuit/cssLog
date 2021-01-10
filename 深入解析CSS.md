# 深入解析CSS

## 过渡transitions

```
transition-property: all; //这个属性可以指定哪些属性使用过渡 例如background-color；width
transition-duration: 0.5s;//代表过渡到最终值之前需要多长时间
```

如果需要为两个不同的属性分别设置不同的过渡，可以添加多个过渡规则，以逗号分隔，如 下代码所示。

```
transition: border-radius 0.3s linear, background-color 0.6s ease;
```

#### 定时函数

定时函数是过渡中非常重要的一部分。过渡让某个属性从一个值“移动”到另一个值，定时 函数用来说明如何移动。是以恒定的速度移动吗？还是开始的时候慢，后面越来越快？

```
linear  //以固定时间过渡
ease-in //开始时慢然后一直加速直到过渡完成
ease-out 是减速，开始时快速变化，结束时比较慢
```

## 变换（transform）

```
旋转（Rotate）——元素绕着一个轴心转动一定角度。
平移（Translate）——元素向上、下、左、右各个方向移动（有点类似于相对定位）。
缩放（Scale）——缩小或放大元素。
倾斜（Skew）——使元素变形，顶边滑向一个方向，底边滑向相反的方向。
```

## 动画(keyframe)
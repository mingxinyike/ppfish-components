## 逐帧动画

长图制作逐帧动画

### 基本使用

:::demo AnimationImageLoader组件图片素材由`src`属性来定义，默认为展示图片。

```js
render(){
  return(
    <AnimationImageLoader/>
  )
}
```
:::

### AnimationImageLoader
| 参数      | 说明    | 类型      | 可选值       | 默认值   |
|---------- |-------- |---------- |-------------  |-------- |
| src     | 动画图地址   | string  |  —  |    示例图     |
| zoom  | 缩放比例    | number   | — | 0.5   |
| extraCls  | 额外的class    | string   | — | —   |